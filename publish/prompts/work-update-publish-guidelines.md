# Work Prompt — Update the Publish Workflow Itself

Use this prompt when the publication process changes and the standing repository instructions should be revised.

---

Work from the private GitHub repository:

`lenkunz/universe-made-of-logic-framework-publish`

Read:

- `publish/README.md`
- `publish/manifest.md`
- `publish/guidelines.md`
- every file under `publish/prompts/`
- `memory/workflow.md`
- `memory/current-context.md`

Then update the publication workflow documents so they match the user's newest intended process.

Preserve these default commitments unless the user explicitly changes them:

- `source/` remains semantic authority;
- `memory/` remains continuity, not semantic authority;
- `publish/manifest.md` owns publication identity and output paths;
- publication Markdown belongs under `publish/articles/`;
- generated publication images belong under `publish/assets/images/<article-slug>/`;
- images are embedded directly into publication Markdown;
- each image may carry `<!-- Image Caption: ... -->` immediately below it;
- companion article references use `<!-- Article Slot: URL: ... -->`;
- URLs come from `source/internal/url-list.md` / the manifest and are never invented;
- the eight primary framework articles are treated as existing publication identities during rebuilds;
- the Hope remains separate unless explicitly included;
- stable files are updated in place instead of producing timestamped publication duplicates.

Also update `memory/workflow.md` if the standing process itself changes materially.

Do not modify framework semantics while updating publication workflow instructions unless the user explicitly requested a semantic update too.
