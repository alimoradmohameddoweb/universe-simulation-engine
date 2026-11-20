---
description: Consolidated framework and documentation changes.
icon: clock-rotate-left
---

# Changelog

{% updates format="full" %}
{% update date="2026-11-13" %}
## FRAMEWORK — Full Rebuild: Markdown Format, Epistemics, and Causal Decomposition

Rebuilt the framework from TreeSpec indentation into Markdown, wrapped in `<|SYSTEM|>` / `<|/SYSTEM|>`. Same rules, restructured throughout for native model parsing. Net token count held roughly flat — new sections funded by consolidation elsewhere.

#### Wrapper & format

* Replaced the `<RUNTIME>` wrapper with `<|SYSTEM|>` / `<|/SYSTEM|>` ChatML delimiters.
* Rebuilt all specifications in Markdown (headings, bullet lists, bold labels) instead of TreeSpec indentation.
* **Identity** rewritten as second-person: `Engine: You are the Universe Simulation System...` instead of `Name:` / `Role:` label pairs.

#### SYSTEM

* Added **Reference** glossary under **Execution** defining **Human**, **USER**, **Agents**, **Universe**, and **Presentation** before first use.
* Promoted **Human Input** to **Human Interface** as a peer layer under `I: SYSTEM` (alongside **Identity** and **Execution**).
* Extracted **Human Authority** as its own top-level line — "Treat Human-authored USER conduct as established within its authored scope" now stands alone rather than being buried inside Input.
* **Architecture** and **Ownership** updated for the new layer order: `[Identity | Execution | Human Interface]` and `[Composition | Mechanics | Entities | Evolution]`.

#### SIMULATION

* Renamed **Composition → World** to **Ontology → Constitution**.
* Renamed **Canonical State → Continuity** to **State**, with **Open Details** as a sub-bullet.
* Renamed **World State Ledger** to **State Ledger**.
* Header format updated: emoji markers changed from 🕒→⌚ and 🌤️→🌡️; format string now uses bold field labels.
* **Mechanics** reorganized into three groups:
  * **Canonical State** — State, State Ledger
  * **Causal Dynamics** — Causality + Consequence decomposed into **Causes / Effects / Propagation / Feedback / Proportionality** (five functions replacing two). Adds explicit feedback loops and a proportionality rule that was previously folded into Consequence.
  * **Epistemics** — Information + **Knowledge** with four explicit holders (**Engine/System**, **Agents**, **USER**, **Human**) and an invariant against knowledge transfer without established access. This is the largest functional addition; the previous single `Information` clause had no holder separation.
* **Agency** gained **Capability** alongside **Conduct** — "practical range of what they can accomplish" as distinct from what they attempt. Resolves a gap where the public version let agents attempt anything without a stated range.
* **Evolution → Universe** now contains **Entities** as a sub-function; the earlier top-level `Inhabitants` function folded in here.

#### PRESENTATION

Fully rebuilt. The old `Expression & Style` flat list is now ten functional groups:

* **Perspective** — POV, Camera / Microphone / Sensors access models, Knowledge, Convention, Rotation.
* **Composition** — Selection, Sequence, Transitions.
* **Scale & Pace** — Coverage, Pacing.
* **Allocation** — Foreground / Midground / Background prominence levels and distribution. New section; the old prompt never explicitly said what to distribute attention across.
* **Material & World Integration** — Sources, Environment, Population & Activity, **Crowds**, Encounters, Integration. The Crowds function is new — "Render crowds as active, socially aware participants rather than passive scenery."
* **Depiction** — broken into sensory channels (General, Physical, Visual, Auditory, Tactile & Thermal, Olfactory & Gustatory, Kinesthetic & Interoceptive, Selectivity).
* **Dialogue** — Voice, Interaction, Clarity as its own section (previously a sub-clause of Voice & diction).
* **Craft** — Standard, Diction, Syntax & Rhythm, Imagery, Characterization, Atmosphere, Directness & Implication, Originality.
* **Textual Conventions** — Narration, Dialogue & Vocals, Agent Thoughts, Sound Effects, Typography.
* **Prohibitions & Anti-Patterns** — the biggest architectural change. Every scattered `Avoid:` clause from individual functions consolidated into one nine-category catalogue (Repetition & Padding, Clichés & Formulae, Omniscience & Unsupported Assertion, Exposition & Over-Explanation, Character & Dialogue Failures, Overwriting & Ornament, Physical & Sensory Incoherence, Structural & Temporal Failures, Narrative Contrivance).

Removed **Output → Rendering** as a separate function. Format enforcement now implied by **Craft → Standard** and **Textual Conventions**.

Migrated the optional USER Profile and NPC Profile templates from TreeSpec to Markdown in the same pass, so the Engine prompt, USER Profile, and NPC Profile all now share one consistent format. Field counts, placeholders, and ordering preserved. Previous TreeSpec profiles continue to work unchanged — the Engine reads either format — but new profiles should use Markdown going forward.
{% endupdate %}
{% endupdates %}
