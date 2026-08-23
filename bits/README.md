# Bits Production Pipeline

Updated: 2026-08-23
Status: ACTIVE BITS WORKFLOW

This directory owns the production package for each **Bits** episode.

Bits are more complicated than ordinary article publication because each episode may need:

- a curated source list for NotebookLM;
- an episode-specific detailed source/dossier;
- a separate Audio Overview prompt;
- a Work prompt for the written companion article;
- a Work-generated article image;
- the final NotebookLM audio file;
- a production/status ledger.

The goal is to keep every episode self-contained so research, audio, article, image, and publication state do not get mixed with another Bit.

## Standard layout

Each Bit gets one stable slug directory:

```text
bits/<bit-slug>/
├── 00-manifest.md
├── 01-sources-to-load.md
├── 02-notebooklm-source.md
├── 03-notebooklm-audio-prompt.md
├── 04-work-prompt.md
├── article/
│   ├── <bit-slug>.md
│   └── <generated-image-file>
└── audio/
    └── <bit-slug>.m4a
```

Use `bits/_template/` as the starting package.

## File roles

### `00-manifest.md`

The control panel for the episode.

It records:

- title and slug;
- central question;
- central payoff;
- status;
- framework status / correspondence status where relevant;
- duplication check against existing Bits;
- expected files;
- publication date and Substack URL after release.

Automation and future chats should inspect this file first when determining an episode's state.

### `01-sources-to-load.md`

A human checklist of sources to add to NotebookLM.

Separate:

- required framework sources;
- Bit-specific framework sources;
- external sources;
- `02-notebooklm-source.md` itself.

For each source, record why NotebookLM needs it.

### `02-notebooklm-source.md`

The detailed episode source/dossier.

This is normally the largest file in the package. It should contain enough context for NotebookLM to build a useful Audio Overview without having to infer the framework from scattered sources.

Recommended structure:

`central mystery`
→ `ordinary external explanation / observations`
→ `what remains conceptually interesting`
→ `framework-native deduction / interpretation`
→ `status and guardrails`
→ `examples / research notes`
→ `desired discussion route`

Where external science is involved, keep **established external information**, **framework interpretation**, and **unresolved/speculative material** visibly separate.

### `03-notebooklm-audio-prompt.md`

Controls the Audio Overview's presentation.

It should not duplicate the entire dossier. Instead it tells NotebookLM:

- what opens the episode;
- what ordinary explanation comes first;
- when the framework enters;
- what productive challenge or tension the hosts should explore;
- what must not be overclaimed;
- what example deserves the most time;
- what the final takeaway should be.

Preferred Bits rhythm:

`ordinary mystery`
→ `standard explanation`
→ `one remaining conceptual question`
→ `framework lens`
→ `explicit test / boundary where relevant`
→ `memorable closing thought`

### `04-work-prompt.md`

Tells Work how to build the written Substack companion article from the package.

The normal Bits article workflow is now:

- Work reads the manifest, source list, detailed source, audio prompt, and relevant canonical framework source;
- Work writes the publication-ready article;
- Work generates the actual editorial image directly;
- Work stores the image under the Bit's `article/` directory and embeds it in the article Markdown;
- Work keeps visible `Article Slot` and `Image Caption` blockquotes as part of the finished public article when they are useful;
- Work removes only internal-only notes such as `Publish Note` or `Image Brief for Work` once their job is done.

There is **no separate Flow-prompt file in the normal Bits pipeline**.

## Audio

Put the final NotebookLM `.m4a` file under:

`bits/<bit-slug>/audio/`

Use a stable filename based on the Bit slug where practical.

## Transcript policy

A transcript is **not required before publication**.

Substack can generate a transcript after publication, and most Bits do not need transcript-level analysis.

If a specific episode needs pre-publication transcript analysis, create a transcript only for that episode as temporary/exception material. Do not make transcript generation a mandatory step for every Bit.

## Image policy

Work generates the article image directly, using the same editorial-image standard as ordinary framework articles.

The Bit package therefore normally contains:

- the final article Markdown;
- the generated image asset;
- visible reader-facing callouts in blockquote form for image captions and related-article handoffs where useful.

Do not create a separate Flow prompt unless the user explicitly wants an alternate/regenerated Flow image workflow for that Bit.

## Visible blockquotes in the final article

Do not use invisible HTML comments for reader-facing article handoffs or image captions.

Use explicit visible blockquotes with stable labels:

```md
> **Article Slot:** URL: https://...
```

```md
> **Image Caption:** concise caption text
```

These are not temporary placeholders anymore. They are part of the final article's visual language and should normally remain visible in Substack after publication.

This has two advantages:

- the related article URL remains directly readable and needs less special slot maintenance;
- the caption and handoff survive ordinary Markdown rendering instead of disappearing like HTML comments.

Internal-only notes are different:

```md
> **Publish Note:** upload the packaged image binary to Substack rather than relying on the private repository URL.
```

```md
> **Image Brief for Work:** describe the visual purpose here.
```

Perform those instructions and remove the internal-only note from the public article once it is no longer needed.

## Topic selection / duplication check

Before starting a new Bit:

1. read `source/internal/bits-topic-checklist.md`;
2. read the newest published/RSS list if available;
3. search the repository for the topic and close synonyms;
4. compare against published and prepared-but-unpublished Bits;
5. only then create the episode package.

A repeated framework concept is allowed when the external topic, question, evidence, or payoff is genuinely new.

## Production ledger

`bits/index.md` tracks where each episode is in production.

This is different from `source/internal/bits-topic-checklist.md`:

- **Bits topic checklist** answers: *Have we already covered this idea?*
- **Bits index** answers: *Where is this episode in production?*

## Default lifecycle

```text
idea
→ duplication check
→ 00-manifest.md
→ 01-sources-to-load.md
→ 02-notebooklm-source.md
→ 03-notebooklm-audio-prompt.md
→ NotebookLM Audio Overview
→ audio/<slug>.m4a
→ 04-work-prompt.md
→ Work generates article + image
→ keep public Article Slot / Image Caption blockquotes
→ Substack publish
→ record URL/date in manifest + bits/index.md
→ optional Substack transcript only if later analysis needs it
```

The package should make a Bit reproducible without requiring the original chat that created it.
