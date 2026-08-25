# Bits Topic Checklist — My GUT Deduction

Updated: 2026-08-25  
Purpose: prevent future Bits packages from duplicating an already-published topic, repeating the same central mechanism with a cosmetic new example, or preparing the same candidate twice.

## How to use this checklist

Before choosing a new Bits topic, check four things:

- [ ] **External topic is new.** The main real-world subject has not already been the center of a Bit.
- [ ] **Central question is new.** A new title is not enough if the episode asks essentially the same question.
- [ ] **Mechanism is not merely repeated.** Reusing a framework concept is fine, but the ordinary topic should make genuinely new work happen.
- [ ] **Examples are not carrying the whole novelty.** If the only difference is swapping one example for another while keeping the same story, treat it as overlap.
- [ ] **Prepared-but-unpublished topics are checked too.**
- [ ] **If an old Bit mentioned the new topic only briefly, a dedicated episode is allowed only when the new piece has substantial independent research and a clearly different question.**

A useful decision rule:

`same phenomenon`
OR
`same central question + same mechanism + similar examples`
→ **do not repeat**

while:

`brief earlier mention`
+
`new research / new central question / new explanatory payoff`
→ **may be developed later**

---

## Publication sync rule

The preferred live publication source is the Cloudflare-proxied Bits RSS:

`https://souta.me/rss/podcasts`

Its upstream source is the Substack podcast RSS:

`https://api.substack.com/feed/podcast/10455398/s/443918.rss`

Because the suggested Bit title is also the title used for publication, exact RSS title matches can be used to move a prepared Bit into the Published section.

If live access is unavailable, use the GitHub-maintained snapshot:

`resource/substack-bits-podcast.rss`

The workflow `.github/workflows/refresh-substack-bits-rss.yml` refreshes that snapshot through the Cloudflare proxy. The snapshot is the durable fallback and should be preferred over guessing from package existence.

For every Bits Topic Pack run:

1. sync this checklist against the live proxied feed when reachable, otherwise the committed snapshot;
2. prepare and instantiate the new Bit package;
3. ensure the new title is recorded under **Prepared but not published** unless already in the feed;
4. sync against the feed again after package preparation;
5. when an exact prepared title appears in RSS, move it to **Published Bits**, preserve its useful metadata, record the RSS publication date and Substack URL, and remove it from Prepared.

A package existing under `bits/` is evidence that it was prepared, not that it was published.

---

# Published Bits

## 2026-08-25

- [x] **Why Does a Crack Turn?**
  - Status: **PUBLISHED**
  - URL: https://soutame.substack.com/p/why-does-a-crack-turn
  - RSS publication time: 2026-08-25 19:03:05 +07:00.
  - External topic: fracture mechanics, crack-path selection, branching, disorder, and evolving local stress fields.
  - Main question: when several continuations are physically possible, why does a crack continue this way rather than another?
  - Framework hook: present ground can carry unequal continuations; direction need not pre-render a route; resolved history becomes coarse consequential ground that constrains later fine resolution.
  - Closest published overlap: **How possibilities earn their physical ground**, **Why Do Rules Create Freedom?**, and **Why precision is a trap**.
  - Why distinct: this is an independently researched materials-science story about path selection, crack-tip mechanics, disorder, and dynamically changing continuation fields rather than a generic possibility/constraint explanation.
  - Package: `bits/why-does-a-crack-turn/`

## 2026-08-23

- [x] **What If Reality Is the Dream That Learned to Anchor Dreams?**
  - Status: **PUBLISHED**
  - URL: https://soutame.substack.com/p/what-if-reality-is-the-dream-that
  - RSS publication time: 2026-08-23 18:31:58 +07:00.
  - Source: `source/the-hope-behind-the-framework.md`
  - Mode: Hope-derived thought experiment / personal metaphysical hypothesis, explicitly not framework ground.
  - Main question: if reality began as logical relation rather than finished objects, what kind of logical organisation could persist long enough to become shared ground?
  - Central payoff: stable reality might be imagined not as the strongest temporary logical world, but as an organisation that turns successful relation into reusable ground and can carry compatible structures that once required separate hosting.
  - Framework hook used as constraint: seated relation becomes ground; coarse compatible possibility need not be fully resolved; hosted and independently seated are distinct; anchoring supplies reusable support.
  - Closest published overlap: **How possibilities earn their physical ground**, **The Universe on a Computational Budget**, and weakly **Why Do Rules Create Freedom?**
  - Why distinct: those episodes explain framework architecture or ordinary constraint/freedom. This Bit owns a metaphysical origin thought experiment about temporary worlds of logic and self-reinforcing shared ground.
  - Important boundary: do not turn this into quantum many-worlds, simulation theory, consciousness-first cosmology, God, or panpsychism.
  - Reserved follow-up: the Hope's **first consciousness / first integrated Aim** branch should remain a separate future Bit.
  - Package: `bits/reality-the-dream-that-learned-to-anchor-dreams/`

## 2026-08-21

- [x] **Why Does an Air Conditioner Have to Make Something Hot to Make You Cold?**
  - Status: **PUBLISHED**
  - URL: https://soutame.substack.com/p/why-does-an-air-conditioner-have
  - Primary topic: vapor-compression refrigeration, pressure, phase change, evaporation, condensation, and heat transfer.
  - Main question: why must an air conditioner make the outdoor side hotter in order to cool the indoor side?
  - Framework hook: one physical cycle as a test case for whether several surfaced quantities can correspond to one deeper relational change; the framework interpretation remains explicitly provisional where heat/pressure mapping is incomplete.
  - Avoid repeating: generic HVAC loop or “cold is moved heat” explanation unless a future Bit isolates a genuinely different thermodynamic question.

## 2026-08-19

- [x] **Why Does Forgetting Help Us Remember?**
  - Primary topic: forgetting, interference, gist memory, reconstruction.
  - Main question: why can losing detail improve memory?
  - Framework hook: stored history is not rendered detail.
  - Avoid repeating: memory-as-compression, forgetting-as-useful-removal, gist surviving lost detail.

## 2026-08-18

- [x] **Why Our Solutions Become Our Anchors**
  - Primary topic: infrastructure, standards, institutions, skills, path dependence.
  - Main question: why do successful solutions later become costly to abandon?
  - Framework hook: solved structure becomes reusable ground and commitment.
  - Avoid repeating: lock-in/path dependence framed primarily as accumulated ground.

- [x] **How High Can a Fish Swim?**
  - Primary topic: environment-dependent possibility, buoyancy, pressure, lift, niches.
  - Main question: how much freedom is created by the environment that supports you?
  - Framework hook: possibility horizon / supportable range.
  - Avoid repeating: organism freedom explained mainly through environmental support range.

- [x] **Why Do Rules Create Freedom?**
  - Primary topic: creativity under constraint, games, music, language, programming.
  - Main question: why can fewer options create more usable freedom?
  - Framework hook: stable constraints create ground for meaningful possibility.
  - Avoid repeating: “constraints create freedom” with a new set of creative examples.

## 2026-08-17

- [x] **When Practice Makes Thinking Disappear**
  - Primary topic: motor learning, expertise, habit, automaticity.
  - Main question: why does practiced action require less conscious work?
  - Framework hook: repeated structure becomes cheap reusable ground.
  - Avoid repeating: habit/practice as converting active computation into seated structure.

- [x] **When Does a Crowd Become a Mind?**
  - Primary topic: collective intelligence, distributed cognition, teams, institutions.
  - Main question: when do relations among individuals become a continuing higher-level participant?
  - Framework hook: hosted collective domain / relation becoming participant.
  - Avoid repeating: emergence-from-many as the main story unless the new topic has a sharply different mechanism.

- [x] **The Permanent Rent of Suppression**
  - Primary topic: suppression, maintenance cost, accommodation versus permanent resistance.
  - Main question: why can preventing an alternative require continuous work?
  - Framework hook: persistent exclusion / absorption economy.
  - Avoid repeating: “suppression costs forever” with only a different social or biological example.

- [x] **Expanding Space is a Shrinking Ruler**
  - Primary topic: cosmological expansion, local versus CMB-based measurements.
  - Main question: can apparent expansion be read through differential contraction / ruler comparison?
  - Framework hook: relational ruler, coarse/fine comparison.
  - Avoid repeating: Hubble mismatch through shrinking-ruler framing.

- [x] **Why precision is a trap**
  - Primary topic: overmeasurement, detail versus useful coarse constraint.
  - Main question: when does more precision hide the pattern that matters?
  - Framework hook: coarse structure can carry useful high-level constraint.
  - Avoid repeating: coarse-versus-fine framed mainly as “too much detail obscures understanding.”

## 2026-08-16

- [x] **The Universe on a Computational Budget**
  - Primary topic: introductory ontology, Levels 0–2, finite resolving capacity.
  - Main question: what remains if matter, space, and time are not primitive?
  - Framework hook: budget, relation, resolution, boundary.
  - Avoid repeating: broad “universe as computational budget” introductions.

- [x] **The expanding universe is an accounting error**
  - Primary topic: supernova duration stretching / cosmological timing.
  - Main question: could redshift/time-stretch partly reflect cross-ground comparison?
  - Framework hook: clocks as local relational rulers.
  - Avoid repeating: supernova time dilation as a general cross-ground accounting story.

- [x] **The Universe Has a Resolution Limit**
  - Primary topic in RSS description: same supernova/redshift/cross-ground timing material as the episode above.
  - Main question: RSS currently repeats the same description as **The expanding universe is an accounting error**.
  - Framework hook: resolution / clock comparison.
  - **Overlap warning:** the RSS metadata itself appears duplicated or reused here. Treat this pair as a high-risk duplicate family until manually checked against the actual audio.

- [x] **James Webb and the resolution mismatch**
  - Primary topic: JWST, distant structure, observer resolution versus distant coarse constraint.
  - Main question: can some apparent deep-time structure reflect a resolution mismatch?
  - Framework hook: coarse/fine cross-ground comparison.
  - Avoid repeating: JWST surprise explained mainly by observer/remote resolution mismatch.

- [x] **the universe is built on 'No'.**
  - Primary topic: exclusion, boundaries, the Cut.
  - Main question: can stable structure begin from what is excluded rather than from added stuff?
  - Framework hook: distinction, boundary, resolution cost.
  - Avoid repeating: “reality is built by saying no” as a foundational intro.

## 2026-08-15

- [x] **the universe is an informational budget**
  - Primary topic: universal relational binding, stars, finite resolution, inverse-square.
  - Main question: why can everything be related while almost none of it is individually resolved?
  - Framework hook: finite relational budget and reach.
  - Avoid repeating: universal connection + limited resolution + inverse-square as the core package.

- [x] **How possibilities earn their physical ground**
  - Primary topic: Lane/Rung relation, possibility before implementation.
  - Main question: how does a possibility become independently supportable?
  - Framework hook: Lane widening versus Rung seating.
  - Avoid repeating: generic Lane/Rung introduction.

- [x] **Gravity is the universe deleting space**
  - Primary topic: gravity, contraction, clocks, coarse background, dark-sector implications.
  - Main question: can gravity-like behavior be read as relational contraction rather than primitive pull?
  - Framework hook: anchoring / differential contraction.
  - Avoid repeating: broad gravity-as-space-contraction overview.

- [x] **Humanity is the ghost haunting AI**
  - Primary topic: AI modelling human drives without biologically inheriting them.
  - Main question: can a system understand a drive without having that drive?
  - Framework hook: hosted logic versus constitutive bias.
  - Avoid repeating: AI “inherits our models but not our biological motives” as the main thesis.

- [x] **Reality is a cosmic accounting system**
  - Primary topic: optics, white light, prism splitting, refraction, transparency, colour.
  - Main question: can several optical effects be read through one resolution-accounting lens?
  - Framework hook: undercommitment / resolution / exchange across grounds.
  - Avoid repeating: general optics bundle unless a future Bit isolates one genuinely new optical question.

- [x] **The Universe Only Renders on a Budget**
  - Primary topic: measurement, apparatus, resolution density.
  - Main question: can the measuring apparatus itself contribute to the local resolving condition?
  - Framework hook: resolution cost / apparatus as participant.
  - Avoid repeating: generic “measurement changes what becomes resolved” framing.

---

# Prepared but not published

- [x] **The Traffic Jam That Nobody Caused**
  - Status: **HOLD / do not use as the next Bit yet**
  - External topic: phantom traffic jams / stop-and-go waves.
  - Main question: how can a stable jam appear without a bottleneck or single culprit?
  - Framework hook: Lane 3, law among lower relations.
  - Exact published duplicate found in RSS: **No.**
  - Exact older file-library match found: **No, outside this newly prepared package.**
  - Conceptual overlap: **moderate to high** with **When Does a Crowd Become a Mind?**
  - Why: both use a many-parts / relations-between-parts story where the larger pattern persists despite changing members.
  - Distinctive material the traffic piece *does* add: instability threshold, backward-moving wave, ring-road experiment, and one-car damping experiment.
  - Decision: keep it in reserve as a future dedicated complex-systems episode, but choose a lower-overlap topic for the next Bits package.

---

# High-overlap families

Use these as warning clusters. A future topic can reuse a framework concept, but it should not simply retell the same public story.

### Constraint / ground / freedom
- Why Do Rules Create Freedom?
- Why Our Solutions Become Our Anchors
- The Permanent Rent of Suppression

### Coarse detail / memory / reuse
- Why Does Forgetting Help Us Remember?
- Why precision is a trap
- When Practice Makes Thinking Disappear
- Why Does a Crack Turn? — published; shares retained constraint, but its ordinary mechanism is fracture path selection

### Collective / emergent organisation
- When Does a Crowd Become a Mind?
- The Traffic Jam That Nobody Caused — prepared, on hold

### Cosmology / remote-resolution comparison
- Expanding Space is a Shrinking Ruler
- The expanding universe is an accounting error
- The Universe Has a Resolution Limit
- James Webb and the resolution mismatch

### Budget / resolution foundation
- The Universe on a Computational Budget
- the universe is an informational budget
- The Universe Only Renders on a Budget
- the universe is built on 'No'.

### Lane / possibility / support
- How possibilities earn their physical ground
- Why Do Rules Create Freedom?
- How High Can a Fish Swim?
- Why Does a Crack Turn? — published; path selection under inherited constraint

### Hope / metaphysical origin thought experiments
- What If Reality Is the Dream That Learned to Anchor Dreams? — published
- Reserve the first-consciousness / integrated-Aim question as a distinct future topic rather than folding it into the same episode.

### Physical correspondence clusters
- Gravity is the universe deleting space
- Reality is a cosmic accounting system
- Why Does an Air Conditioner Have to Make Something Hot to Make You Cold? — thermodynamic test case, with framework mapping still provisional

---

# Selection rule for future Bits

Prefer a new topic when it brings at least **two** of these:

- [ ] a new external field or phenomenon;
- [ ] a new general-audience question;
- [ ] new research or evidence not already central to another Bit;
- [ ] a different causal tension;
- [ ] a framework concept that has not recently been foregrounded;
- [ ] a substantially different narrative shape.

Reject or hold a topic when:

- [ ] its novelty is mostly a new metaphor for an old Bit;
- [ ] the same framework concept and same ordinary mechanism would carry most of the episode;
- [ ] it is already a prepared-but-unpublished candidate;
- [ ] it substantially overlaps one of the high-overlap families above.

---

# Next-run instruction

Before preparing a new Bits package:

1. Sync this checklist against `https://souta.me/rss/podcasts` when reachable, otherwise `resource/substack-bits-podcast.rss`.
2. Search current framework sources for the candidate topic and close synonyms.
3. Compare the candidate against both exact titles and the overlap families.
4. Only then research and draft the package.
5. Add the selected title to **Prepared but not published** when the package is created.
6. Sync the checklist against the feed again after preparation and move any exact title matches to **Published Bits**.

A topic mentioned briefly in an older Bit is **not automatically banned**. It should become a dedicated Bit only when the new piece has enough independent research, a distinct central question, and a different payoff to justify the repetition.
