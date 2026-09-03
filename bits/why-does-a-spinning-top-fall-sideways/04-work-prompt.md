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

`article/why-does-a-spinning-top-fall-sideways.md`

Also generate the actual editorial image for the article and store it in the same Bit package under `article/` with a sensible filesystem-safe filename. Embed it in the Markdown using a relative link.

Do not create a separate Flow-prompt file unless explicitly requested.

## Episode-specific article focus

Title: **Why Does a Spinning Top Fall Sideways?**

Subtitle direction: **Gravity is still pulling it down. Spin changes what that pull can change first.**

Lead with the familiar tabletop contradiction. A tilted top at rest falls. A fast-spinning tilted top precesses. Explain ordinary mechanics before introducing framework vocabulary.

The article should make these points cleanly:

1. gravity produces torque about the pivot;
2. torque changes angular momentum, `τ = dL/dt`;
3. a non-spinning top starts near zero angular momentum and tips;
4. a fast-spinning top already has a large `L`, so a largely perpendicular torque changes its direction and the axis precesses;
5. under the simple steady fast-precession approximation, `ω_P = rMg/(Iω)`, so faster spin can mean slower precession;
6. real tops nutate, dissipate energy, slow, and eventually fall;
7. a held bicycle wheel is a useful tactile demonstration, but gyroscopic effects alone are not a complete explanation of bicycle stability;
8. only then bring in the framework: a new relation resolves against accumulated ground rather than an empty state;
9. explicitly state that this is an analogy/interpretive lens, not a framework derivation of angular momentum or precession.

## Google Flow / hero-image concept

Create a **16:9 editorial landscape** image of a real wooden or metal spinning top caught at a dramatic tilt on a simple dark tabletop. The top itself should be crisp at the pivot and body, while its axis/upper silhouette leaves a subtle circular sweep through space, visually suggesting that the expected downward fall has been redirected into sideways precession. Include one small non-spinning top lying fallen in the distant background as a quiet contrast, not a diagram. Strong directional lighting, physical textures, restrained photographic/editorial realism. Keep generous clean negative space on the left or upper-left for title placement. The central visual tension is **same gravity, different response because motion is already present**.

Avoid arrows, vector labels, equations, glowing energy, sci-fi rings, galaxies, generic cosmic imagery, infographic styling, baked-in title text, and anything implying a mysterious anti-gravity force.

Suggested visible caption:

> **Image Caption:** Gravity still supplies the torque. Spin changes whether that torque first topples the axis or turns its direction.

## Article standard

Use simple words, familiar question first, ordinary external explanation before framework interpretation, clean pacing, and enough white space. The article is a companion to the audio, not a transcript.

Preferred shape:

`ordinary mystery`
→ `torque and angular momentum`
→ `why the response turns sideways`
→ `faster-spin/slower-precession surprise`
→ `real-motion caveats`
→ `framework lens`
→ `explicit status boundary`
→ `memorable closing thought`

## Semantic discipline

Preserve current framework meaning. Keep external mechanics distinct from framework interpretation.

Do not claim:

- spin cancels gravity;
- angular momentum is a force;
- a spinning top cannot fall;
- the simple steady-precession equation describes all top motion;
- gyroscopic effects alone explain bicycle stability;
- angular momentum, torque, spin, or energy equals computational budget;
- My GUT Deduction derives gyroscopic precession.

The framework contribution here is intentionally modest: present/accumulated ground changes the conditions under which a new relation resolves.

## Image generation

Work should generate the image directly from the episode-specific concept above. Prefer 16:9. No embedded title text, labels, equations, infographic arrows, or generic cosmic-AI decoration. Use descriptive alt text and keep the useful visible Image Caption blockquote in the public Markdown.

## Final QA

Before finishing:

1. confirm the article matches the Bit dossier;
2. confirm external mechanics and framework interpretation remain distinct;
3. confirm no new primitive or stronger framework status was invented;
4. confirm the article is readable without the audio;
5. confirm the image is generated and embedded;
6. confirm the bicycle caveat and fast-precession approximation are not overstated;
7. confirm the visible Image Caption remains where useful;
8. confirm internal-only production notes are removed;
9. update the manifest to `article-ready` only when the article/image are actually complete.
