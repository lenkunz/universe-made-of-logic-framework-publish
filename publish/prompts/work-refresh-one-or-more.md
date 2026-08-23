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
3. preserve/add `<!-- Article Slot: URL: ... -->` comments using only known URLs;
4. generate any hero/inline image the final article needs;
5. save generated images under the article's registered `publish/assets/images/<slug>/` folder;
6. embed the images directly with relative Markdown syntax;
7. add `<!-- Image Caption: ... -->` directly below each image;
8. keep the output semantically faithful to current source.

Do not copy stale article prose merely because the publication already exists.
Do not invent URLs or framework claims.
