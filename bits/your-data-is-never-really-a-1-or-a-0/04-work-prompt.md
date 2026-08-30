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

`article/your-data-is-never-really-a-1-or-a-0.md`

Also generate the actual editorial image for the article and store it in the same Bit package under:

`article/<generated-image-file>`

Embed the image in the Markdown using a relative link.

Do not create a separate Flow-prompt file unless explicitly requested.

## Episode-specific article focus

Title: **Your Data Is Never Really a 1 or a 0**  
Subtitle: **How noisy matter, thresholds, and error correction make digital certainty possible**

Open with the ordinary technology puzzle: where is the perfect `1` if the memory device is physical, noisy, and tolerant?

Build the reader-facing article through:

`magnetic storage stability`
→ `NAND threshold regions`
→ `logical decisions from physical ranges`
→ `error correction`
→ `error tolerance versus lossy reconstruction`
→ `physical sameness ≠ logical sameness`
→ framework lens late in the article.

The key current framework wording is:

> **Stored constraint is not the same thing as rendered detail.**

Use `source/basics-2-coarse-is-not.md` as semantic authority. Do not fall back to older shorthand if it changes that meaning.

The framework comparison should remain narrow: engineering gives an ordinary example where exact logical interpretation can survive without microscopic physical sameness. That does **not** prove the universe stores history as bits, NAND states, error-correcting codes, or compressed files.

## Article standard

Use:
- simple words;
- familiar question first;
- ordinary external explanation before framework interpretation;
- clean conceptual pacing;
- enough white space;
- no jargon pile;
- no unnecessary recap of the entire framework;
- no claim inflation;
- strong final thought rather than a sales pitch.

## Semantic discipline

Keep external engineering distinct from framework-native interpretation.

Do not invent a numerical prediction, equation, universal error threshold, or physical-universe decoding mechanism.

Do not say error correction and lossy compression are the same thing.

## Image generation

Generate a 16:9 editorial conceptual image directly.

### Episode-specific visual concept

Show **messy physical states becoming one crisp logical reading**.

Use a tactile field of magnetic-grain / charge-like physical states with visible small variations. Let broad threshold zones or a clean decision boundary sort those imperfect states into stable discrete categories. The threshold/sorting mechanism is the focal concept. One side should feel physical and variable; the resolved side should feel crisp and logical.

Leave useful negative space for title placement.

Avoid:
- embedded title text;
- labels or equations;
- infographic arrows;
- framework diagrams;
- neon cyberpunk;
- glowing brains;
- galaxies;
- holographic UI;
- binary rain;
- generic circuit-board stock imagery.

Use descriptive alt text.

When a caption helps:

> **Image Caption:** Digital certainty does not require every physical state to be identical. It requires the differences that matter to remain recoverable.

Keep the caption visible in the public Markdown.

## Article cards / related-article handoffs

The nearest conceptual published handoff is **Why Does Forgetting Help Us Remember?**

Use an established repository URL only if it is available. Never invent one.

If useful and the exact URL is confirmed:

> **Article Slot:** URL: <confirmed URL>

Otherwise leave the slot empty for later completion.

## Final QA

1. confirm magnetic storage, NAND thresholds, ECC, and lossy/lossless material are represented accurately;
2. confirm external engineering and framework interpretation remain visibly separate;
3. confirm `source/basics-2-coarse-is-not.md` wording is preserved;
4. confirm the article does not retell **Why Does Forgetting Help Us Remember?** as a technology metaphor;
5. confirm the image is generated and embedded;
6. confirm no new primitive or stronger framework status was invented;
7. confirm the article is readable without the audio;
8. confirm internal-only production notes are removed before publication;
9. update the manifest to `article-ready` when production actually reaches that state.
