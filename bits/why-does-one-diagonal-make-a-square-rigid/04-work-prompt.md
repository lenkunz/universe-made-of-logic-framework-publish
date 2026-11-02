# Work Prompt — Build This Bit for Substack

Use this Bit package as the production basis:

- `00-manifest.md`
- `01-sources-to-load.md`
- `02-notebooklm-source.md`
- `03-notebooklm-audio-prompt.md`
- relevant current framework source/status files already available in the Work

This is a **presentation-layer build**, not a semantic rewrite.

## Output

Create the publication-ready written companion article at:

`article/why-does-one-diagonal-make-a-square-rigid.md`

Also generate the actual editorial image for the article and store it in the same Bit package under:

`article/<generated-image-file>`

Embed the image in the Markdown using a relative link.

Do not create a separate Flow-prompt file unless explicitly requested.

## Episode-specific article focus

Title: **Why Does One Diagonal Make a Square Rigid?**

Subtitle direction: **Four stiff bars can still make a floppy frame. One extra relation can remove the motion.**

Lead with the tangible tabletop puzzle: four rigid bars with pin joints can rack from a square into a diamond without any bar changing length. Then add one diagonal and show why the free shear disappears. Explain triangles, fixed distances, degrees of freedom/mechanisms, and the difference between geometric rigidity and real-world structural strength before introducing any framework language.

The main conceptual payoff is not “triangles are strong.” It is sharper: **the inventory of pieces can stay almost the same while the constraint network changes the capability of the whole.** One well-placed relation can remove a motion that all previous relations permitted.

Framework connection should remain narrow: relation can become consequential structure; a larger relational structure can participate as one while its inner relations keep acting. Label the truss connection as candidate structural correspondence. Do not claim that the framework derives rigidity theory or engineering mechanics.

Useful counterexample: adding a redundant or badly placed member does not necessarily remove a new degree of freedom. This protects the article from collapsing into “more relations = more rigidity.”

## Google Flow / hero-image concept

Create a **16:9 editorial landscape** image showing two small tabletop frames made from identical slim wooden or metal bars with visible pin joints. Center-right, place them side by side: the left four-bar frame is visibly racked into a diamond even though every bar remains straight and intact; the right frame has one clean diagonal brace and holds a crisp square/rectangular shape.

The central visual tension is **the same four-edge structure changing from a movable linkage to a rigid frame because one strategically placed connection closes the motion**. Make the diagonal unmistakable but visually simple. Use restrained studio/editorial lighting, realistic materials, and generous clean negative space on the left for title placement.

Avoid arrows, equations, force labels, glowing joints, impossible deformation, broken bars, construction-site clutter, generic bridge glamour shots, framework diagrams, sci-fi styling, galaxies, brains, generic AI imagery, and baked-in title text. Do not imply that the unbraced frame bends because its bars are soft; the bars should remain straight while the joints rotate.

## Article standard

Use the same reader-facing style as the current framework publication work:

- simple words;
- familiar question first;
- ordinary external explanation before framework interpretation when science is involved;
- clean conceptual pacing;
- enough white space;
- no jargon pile;
- no unnecessary recap of the entire framework;
- no claim inflation;
- strong final thought rather than a sales pitch.

The article is a companion to the audio, not a transcript of it.

A useful default shape is:

`ordinary mystery`
→ `standard explanation`
→ `remaining conceptual question`
→ `framework lens`
→ `test / boundary where useful`
→ `memorable closing thought`

## Semantic discipline

Preserve current framework meaning.

Keep external observations / established explanation distinct from framework-native interpretation.

Do not invent a numerical prediction, equation, or quantitative completion unless the source package actually contains it.

Do not import conventional ontology when doing so changes framework primitives.

Do not use older publication prose as semantic authority over newer source.

Episode-specific guards:

- geometric rigidity is not the same as unlimited strength;
- ideal pin joints are a model, not a literal description of every real truss;
- a physical brace is not literally framework `R_AB`;
- framework budget is not stiffness, force, stress, strain, member count, or degrees of freedom;
- do not claim every added relation increases rigidity.

## Image generation

Work should generate the image directly.

Choose one strong conceptual relationship from the finished article and create an editorial conceptual image that helps the reader understand it.

Prefer 16:9 for the hero image unless the article clearly needs another format.

Avoid:

- embedded title text;
- labels or equations;
- infographic arrows;
- generic cosmic-AI decoration;
- visuals that silently turn candidate correspondence into established ontology.

Use descriptive alt text in the Markdown.

When a caption helps the reader, put this visible blockquote directly below the image:

> **Image Caption:** Four rigid sides can still shear when the joints are free to rotate. One diagonal fixes another distance and removes that motion in the ideal linkage.

The **Image Caption blockquote is part of the final public article**. Keep it visible in the Markdown and in Substack unless there is a specific editorial reason to omit that caption entirely.

Do **not** replace it with a hidden HTML comment.

## Article cards / related-article handoffs

When a related framework article should be surfaced, use a visible blockquote:

> **Article Slot:** URL: https://...

Use only established URLs from the repository. Never invent one.

If the URL is not known:

> **Article Slot:** URL:

leave it empty for later completion.

The **Article Slot blockquote is also part of the final public article**. Keep it visible as the reader-facing handoff rather than converting it into a hidden slot marker.

Do **not** use `<!-- ... -->` HTML comment markers for article slots or image captions.

## Internal-only notes

If Work needs a temporary production instruction, use a labelled visible blockquote such as:

> **Publish Note:** ...

or:

> **Image Brief for Work:** ...

These are different from Article Slot / Image Caption. Perform the instruction and remove the internal-only note before final public delivery once it has served its purpose.

## Final QA

Before finishing:

1. confirm the article matches the Bit dossier;
2. confirm external science and framework interpretation remain distinct;
3. confirm no new primitive or stronger status was invented;
4. confirm the article is readable without the audio;
5. confirm the image is generated and embedded;
6. confirm reader-facing `Article Slot` and `Image Caption` blockquotes remain visible where useful;
7. confirm internal-only `Publish Note` / `Image Brief for Work` markers have been removed once completed;
8. confirm no hidden HTML production markers were introduced;
9. confirm the package manifest can be updated to `article-ready` or later.
