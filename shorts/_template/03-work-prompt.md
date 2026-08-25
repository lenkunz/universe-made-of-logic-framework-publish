# Work Prompt — Build This Short for Substack

Use this Short package as the production basis:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-short-source.md`
- relevant current framework source/status files already available in the Work

This is a presentation-layer build, not a semantic rewrite.

## Output

Create the publication-ready Short at:

`article/<slug>.md`

Also generate the actual editorial image for the Short and store it in the same Short package under:

`article/<generated-image-file>`

Embed the image in the Markdown using a relative link.

Do not create audio or NotebookLM files for Shorts unless explicitly requested.

## Short standard

Keep the piece narrow and readable:

- one clear question or claim;
- familiar opening before framework vocabulary;
- mechanism first;
- framework connection only where it adds value;
- simple words and clean pacing;
- no framework-wide recap unless required;
- preserve exact claim status;
- end on the Short's own payoff rather than a sales pitch.

## Semantic discipline

Use current framework source and `source/where-the-framework-stands.md` as semantic authority.

Preserve still-valid prepared prose, but correct anything newer source has superseded.

Keep external established information distinct from framework-native interpretation.

Do not invent a new primitive, numerical completion, or stronger claim status.

## Image generation

Work should generate the image directly, using the episode-specific image concept in `02-short-source.md` as the starting brief.

Choose one strong conceptual relationship from the finished Short and create an editorial conceptual image that helps the reader understand it.

Prefer 16:9 for the hero image unless the Short clearly needs another format. Leave useful negative space for title placement when composition permits.

Avoid embedded title text, labels, equations, infographic arrows, generic cosmic-AI decoration, and visuals that silently turn speculative correspondence into established ontology.

Use descriptive alt text in the Markdown.

When a caption helps, place this visible blockquote directly below the image:

> **Image Caption:** concise caption text

Keep reader-facing image captions visible in the final Markdown. Do not replace them with hidden HTML comments.

## Related-article handoff

When a related framework article should be surfaced, use:

> **Article Slot:** URL: https://...

Use only established URLs from the repository. Never invent one. If the URL is unknown, leave the URL field empty.

## Final QA

Before finishing, confirm the Short still matches `02-short-source.md`, current semantic source wins over older wording, claim status is preserved, the image has been generated and embedded, useful reader-facing captions/article slots remain visible, and no hidden HTML production markers were introduced.
