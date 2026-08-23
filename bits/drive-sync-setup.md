# NotebookLM Google Drive Sync — One-Time Setup

Updated: 2026-08-23
Status: SETUP REQUIRED ONCE

The repository now contains a GitHub Action at:

`.github/workflows/sync-notebooklm-drive.yml`

It automatically mirrors the NotebookLM-facing Markdown from GitHub into a dedicated Google Drive folder whenever relevant content changes on `main`.

## Drive destination

Parent folder:

**Universe Made of Logic - NotebookLM**

Dedicated machine-managed mirror folder:

**GitHub Mirror**

Drive folder ID:

`184xff-AZCE94oWyNwh826M7IYNeRReLE`

The GitHub Action is scoped directly to this folder ID.

Do not put manually maintained files inside **GitHub Mirror**. The workflow uses `rclone sync`, so files in this mirror that are not present in the generated GitHub-side mirror can be removed.

Manual NotebookLM material can safely live beside `GitHub Mirror` in the parent folder.

---

# Why OAuth / rclone is used

A standalone Google service account cannot own ordinary My Drive files because service accounts do not have personal Drive storage quota.

This project therefore uses **your own Google Drive OAuth session through rclone**.

That means synced files are written as your Drive user rather than as a zero-quota service account.

The OAuth credential is stored only as an encrypted GitHub Actions repository secret value.

---

# One-time setup

## 1. Install rclone on a computer where you can sign into the Google account that owns this Drive

Use the official rclone installation for your OS.

Then run:

```bash
rclone config
```

Create a new remote with this exact name:

```text
gdrive
```

Choose **Google Drive** as the storage type and complete the browser OAuth login using the Google account that owns the NotebookLM folder.

Default settings are normally sufficient.

## 2. Test the remote

Run:

```bash
rclone lsd gdrive:
```

You should see folders from your Drive.

## 3. Find your rclone config file

Run:

```bash
rclone config file
```

The output tells you where `rclone.conf` is stored.

That file contains the OAuth refresh token. Treat it as a password.

## 4. Convert the config to Base64

### macOS / Linux

```bash
base64 < ~/.config/rclone/rclone.conf | tr -d '\n'
```

If your config lives elsewhere, use the path returned by `rclone config file`.

### Windows PowerShell

First use `rclone config file` to locate the file, then run something equivalent to:

```powershell
[Convert]::ToBase64String([IO.File]::ReadAllBytes("C:\path\to\rclone.conf"))
```

Copy the resulting single-line Base64 value.

## 5. Add the GitHub Actions secret

In the repository:

**Settings → Secrets and variables → Actions → New repository secret**

Create:

```text
Name: RCLONE_CONFIG_BASE64
Value: <the Base64 string from step 4>
```

Never commit `rclone.conf` or its Base64 form into the repository.

## 6. Run the workflow once manually

Open:

**Actions → Sync NotebookLM Drive → Run workflow**

After it completes, check:

**Google Drive → Universe Made of Logic - NotebookLM → GitHub Mirror**

The folder should contain:

```text
framework/
bits/
```

---

# What gets synced

## `framework/`

All Markdown files under repository `source/`, preserving subfolders.

This includes current semantic source plus internal source notes that may be useful when deliberately selected in NotebookLM.

## `bits/`

For each real Bit package, excluding `_template`, the mirror includes:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-notebooklm-source.md`
- `03-notebooklm-audio-prompt.md`

It also includes:

- `_production-index.md`

which mirrors repository `bits/index.md`.

The sync deliberately excludes:

- `04-work-prompt.md`
- generated article Markdown
- generated images
- podcast/audio files
- template files

Those are not normally NotebookLM sources.

---

# Automatic trigger

After setup, the workflow runs automatically on pushes to `main` that change:

- `source/**`
- `bits/**`
- the sync workflow itself

It can also be run manually with `workflow_dispatch` from the GitHub Actions page.

---

# NotebookLM behavior

The Drive mirror keeps stable file paths and rclone updates files in place when possible.

In NotebookLM, import the files from Google Drive rather than re-uploading local copies whenever possible. This makes later source refresh much easier.

NotebookLM supports Markdown files as sources. Google Drive-imported sources can be refreshed/synced from their original Drive source when NotebookLM detects changes.

For each Bit, `01-sources-to-load.md` remains the human checklist telling you which mirrored framework files and which episode dossier should be selected.

---

# Security rule

`RCLONE_CONFIG_BASE64` grants access to the Drive scope authorized during rclone setup.

Therefore:

- keep it only in GitHub Actions Secrets;
- never paste it into Markdown, issues, commits, or chat logs;
- rotate/revoke the rclone OAuth token if the secret is ever exposed;
- keep this repository private unless the credential setup is removed first.

---

# Normal workflow after setup

```text
edit/sync framework or Bit package in GitHub
→ push/commit to main
→ GitHub Action builds a clean NotebookLM mirror
→ rclone syncs it to Google Drive
→ open NotebookLM
→ select the Drive files listed by the Bit's 01-sources-to-load.md
→ generate / refresh the Audio Overview
```

Once the one-time OAuth secret is installed, there should be no repeated manual copying of Markdown into Drive.
