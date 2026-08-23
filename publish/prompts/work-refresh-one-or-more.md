# Work Prompt — Refresh One or More Published Framework Articles

Use this prompt when only part of the eight-article publication set needs rebuilding.

---

Work from the private GitHub repository:

`lenkunz/universe-made-of-logic-framework-publish`

Read:

- `publish/README.md`
- `publish/manifest.md`
- `publish/guidelines.md`
- `memory/current-context.md`
- the target semantic source file(s)
- `source/where-the-framework-stands.md` if claim status matters
- relevant semantic change maps
- `source/internal/url-list.md`

## Target article(s)

[Specify the target article names or source paths here.]

## Task

For each target article:

1. rebuild the publication Markdown from the current source;
2. write/update the stable path registered in `publish/manifest.md`;
3. preserve/add visible `> **Article Slot:** URL: ...` blockquotes using only known URLs and keep them in the final public article;
4. generate any hero/inline image the final article needs;
5. save generated images under the article's registered `publish/assets/images/<slug>/` folder;
6. embed the images directly with relative Markdown syntax;
7. when a caption is useful, add `> **Image Caption:** ...` directly below the image and keep it visible in the final public article;
8. use `> **Publish Note:** ...` or `> **Image Brief for Work:** ...` only for temporary internal instructions, then remove them after the instruction has been completed;
9. keep the output semantically faithful to current source.

The visible **Article Slot** and **Image Caption** blockquotes are now part of the intended publication presentation. Do not convert them into special embeds merely because the article is ready to publish.

Do not use hidden `<!-- ... -->` HTML comments for article slots, image captions, or production instructions.
Do not copy stale article prose merely because the publication already exists.
Do not invent URLs or framework claims.
