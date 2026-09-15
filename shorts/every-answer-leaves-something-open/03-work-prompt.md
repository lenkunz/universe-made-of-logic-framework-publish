# Work Prompt — Build This Short for Substack

Use this Short package as the production basis:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-short-source.md`
- newest relevant framework source/status files from GitHub

This is a presentation-layer build, not a semantic rewrite.

## Output

Create the publication-ready Short at:

`article/every-answer-leaves-something-open.md`

Generate the actual editorial image directly during the build and store it under this same Short package at:

`article/<generated-image-file>`

Embed it in the Markdown using a relative link and descriptive alt text.

Do not create audio, NotebookLM source, or NotebookLM prompt files.

## Editorial job

Preserve the prepared Short's narrow question: why settling one consequential distinction does not require settling every finer distinction around it.

Keep the door opening because it makes the mechanism legible before framework vocabulary appears. Tighten rhythm if useful, but do not replace the central mechanism with a different metaphor.

The progression should remain:

`ordinary answered question`
→ `one distinction becomes consequential`
→ `other distinctions need not yet matter`
→ `Cut = resolution at that grain`
→ `resolved distinction + unresolved remainder`
→ `the answer becomes new ground for later questions`
→ final payoff

Use simple words. Avoid a framework-wide recap.

## Semantic discipline

Use `source/a-universe-made-of-logic.md` and `source/where-the-framework-stands.md` as semantic authority, with newer GitHub source winning over older prepared wording.

Preserve these boundaries:

- the seated Cut is resolution at that grain;
- the same Cut leaves distinctions it does not need unresolved relative to the new ground;
- unresolved alternatives do **not** each require separate fine seating;
- do **not** say widening is free;
- do **not** imply that every unresolved alternative is an independently rendered branch;
- do **not** turn the door analogy into established external physics;
- do **not** introduce candidate physical correspondences unless absolutely needed. They are not needed for this Short.

Preserve the final line if current source still supports it:

> **An answer does not only close a question. It creates the ground from which the next unanswered differences can exist.**

## Image generation

Generate one editorial 16:9 conceptual image from the episode-specific image concept in `02-short-source.md`.

Preferred composition: a partly open physical door in a quiet simple room. The decisive relational fact, that passage is open, should read immediately. The doorway and usable opening are crisp. Finer detail around the hinge, microscopic wood texture, and non-consequential background can transition into gentle under-specification. This should feel like selective commitment, not camera focus gimmickry.

Leave useful negative space for title placement. No embedded title text, labels, equations, infographic arrows, generic cosmic/AI decoration, or sci-fi styling.

Place the image near the opening. When useful, keep a visible caption such as:

> **Image Caption:** The opening can be settled without every finer detail of the door being settled with it.

## Related article

Keep the visible Article Slot only if the URL is verified against repository/publication data. Never invent or repair a URL by guess. If the prepared URL is not established, leave the URL field empty.

## Final QA

Confirm that the article still owns the single-Cut architecture rather than drifting into the accumulated-history territory of `The Future Does Not Start from Zero`, perception/rendering territory, or a generic essay about uncertainty. Confirm current semantic source wins, the image is generated and embedded, visible Image Caption / Article Slot blockquotes remain where useful, and no hidden HTML production markers are introduced.
