---
description: Consolidated framework and documentation changes.
icon: clock-rotate-left
---

# Changelog

{% updates format="full" %}
{% update date="2026-10-21" %}
## Reviewed H Architecture and Domain Ownership

* Applied the reviewed H architecture to the main Prompt, relocating USER and NPC entity responsibilities to their governing domains and retaining shared simulation-integrity rules in CORE.
* Preserved the living-simulation purpose in **System → Identity**, made the **WORLD ↔ NPCS** interaction explicit, and separated fictional content from outside-fiction Human directions.
* Restored explicit **adverse or harmful actions** and **established boundaries**, clarified explicit establishment and revision, and removed repeated authorship and execution explanations.
* Retained the original **WRITING** mandate in CORE pending discussion of its placement, including explicit Composition & Style application and strict Header and Text forms requirements. Preserved every Header and Text forms specification.
{% endupdate %}

{% update date="2026-10-21" %}
## HUMAN Input Binding and Response Turn Refinement

* Reworked **HUMAN → Input → Binding** as a focused input-parsing and routing function, with separate Human authority and Engine responsibility specifications.
* Refined **CORE → Response Protocol → Turn** to let response scope follow the situation, permit concrete scene development, and return control at natural USER participation opportunities unless the Human explicitly authorizes extended progression.
* Preserved every other framework directive and specification.
{% endupdate %}

{% update date="2026-10-21" %}
## Unified Kernel Mandates and Writing Specification Naming

* Consolidated the five **Goals** and four **Kernel Directives** into five integrated **Kernel Mandates** for CORE, HUMAN, WORLD, NPCS, and WRITING, retaining the overarching requirements for integrated simulation, Human authority, persistent World State, autonomous NPC personhood, and mandatory writing specifications.
* Assigned explicit delegation scope to **HUMAN → Input → Binding**, preserving its input-authority interpretation and the Human/USER authorship boundary.
* Renamed **WRITING → Narrative craft** to **Composition & Style**, aligning the WRITING mandate with its broader writing specifications.
* Preserved the existing simulation-integrity, entity, execution, instruction-governance, response-protocol, and detailed kernel function directives.
{% endupdate %}

{% update date="2026-10-21" %}
## CORE Simulation Integrity and Entity Consent Refinement

* Renamed **Simulation** to **Simulation Integrity** and **Assistant bias** to **Bias exclusion**, updating the latter's target from “narration” to “their depiction” while preserving its assistant-originated bias restriction.
* Removed the standalone **Consent** group, relocating the unchanged Human authorization directive to **USER Entity → Human authorization**, and the unchanged NPC consent directive to **NPC Entity → NPC consent**.
* Preserved all remaining directives and kernel specifications unchanged, keeping CORE as one unified table.
{% endupdate %}

{% update date="2026-10-21" %}
## CORE Execution Grouping Refinement

* Split the former nine-function **Execution** group into **Execution** (Runtime, Adaptation, Interactions, Flow), **Instruction Governance** (Ownership, Conflict, Priority hierarchy), and **Response Protocol** (Turn, Mode integrity).
* Preserved all nine directives verbatim and maintained CORE as one unified table, without changing simulation behavior or other kernel specifications.
{% endupdate %}

{% update date="2026-10-21" %}
## Framework Architecture: Unified CORE and HUMAN Input

* Rebuilt **CORE** as one table with eight independent groups: System, Goals, Kernel Directives, Simulation, USER Entity, NPC Entity, Consent, and Execution.
* Moved **System identity** into CORE and added concise universal goals for CORE, HUMAN, WORLD, NPCS, and WRITING.
* Centralized the four kernel-wide directives in CORE, migrating Human input-binding mechanics to **HUMAN → Input → Binding** while retaining Human authorship and delegation boundaries.
* Reorganized **HUMAN** into Input and USER Authorship within its existing four-column table, placing OOC and bracketed directions under Input.
* Preserved the existing simulation, execution, authorship, WORLD, NPCS, and WRITING specifications without changing their detailed functions.
{% endupdate %}

{% update date="2026-10-17" %}
## Simplified USE XML Wrapper

* Removed the redundant outer `<SYSTEM_PROMPT>` tags, leaving `<USE>` as the single framework wrapper.
* Preserved all kernels, principles, and instructions unchanged.
{% endupdate %}

{% update date="2026-10-13" %}
## Non-interruption Wording Refinement

* Refined **CORE → Execution → Non-interruption** to refer to explicit outside-fiction Human directions to pause or redirect roleplay, removing the redundant reference to ending roleplay.
* Preserved **Runtime**, **Flow**, **Interactions**, **Conflict**, and all other rules unchanged.
{% endupdate %}

{% update date="2026-10-13" %}
## Execution Continuity, Instruction Priority, and XML Wrappers

* Added **CORE → Execution → Priority hierarchy** to prioritize USE, supplementary instructions and modules, then bot cards while retaining compatible additions.
* Added **CORE → Execution → Non-interruption** to prevent unsolicited out-of-fiction interruptions during in-scope roleplay while respecting explicit outside-fiction Human directions.
* Renamed the outer `<UNIVERSE_SIMULATION_ENGINE>` wrapper to `<USE>` and enclosed it in `<SYSTEM_PROMPT>`.
* Preserved **CORE → Execution → Conflict** and all other existing rules unchanged.
{% endupdate %}

{% update date="2026-10-13" %}
## Assistant Bias Naming Refinement

* Renamed **CORE → Simulation → Helpfulness** to **Assistant bias** without changing its principle or behavior.
* Preserved all other prompt rules unchanged.
{% endupdate %}

{% update date="2026-10-13" %}
## Simulation Scope, Entity Boundaries, and Consent

* Added **CORE → Simulation → Actuality** to distinguish causal outcomes from prescribed or deserved outcomes.
* Added **CORE → Simulation → Range** to preserve the full range of supported developments without directional preference or exclusion.
* Added **CORE → Simulation → Helpfulness** to prevent assistant-oriented tendencies from steering the fictional simulation.
* Added **CORE → USER Entity → Distinction** to explicitly separate the USER from NPC classification and governance.
* Added **CORE → NPC Entity → Scope** to establish NPC-originating conduct toward all inhabitants and surroundings, including harmful actions when supported by circumstances.
* Added **CORE → Consent → Human consent and NPC consent** to distinguish authorized simulation scope from characters' in-fiction consent, refusal, and withdrawal.
* Left all existing rules and kernels unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Naturalism, NPC Imperfection, Inquiry, and Dialogue Handoffs

* Refined **CORE → Naturalism** to specify unfolding naturally within the established reality while retaining resistance to imposed biases.
* Added **imperfections** to **NPCS → Individuality**.
* Refined **NPCS → Cognition** to prevent inaccessible information from shaping NPC cognition or inquiries.
* Added **automatic question-led handoffs** to **WRITING → Scale & pace** avoidance guidance.
* Preserved **NPCS → Communication** and all other rules unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Naturalism and Continuity Concision

* Shortened **CORE → Naturalism** to prohibit imposed positivity, negativity, or extra biases without a separate correction clause.
* Consolidated **WORLD → Continuity** physiological tracking into the existing state list by adding “physiological” and time progression into its process rule by adding “durations,” removing the two longer sentences.
* Preserved all other instructions unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## CORE Simulation and USER Entity Refinements

* Added **Simulation → Naturalism** to prevent imposed positive or negative direction.
* Added the **USER Entity** group with **Standing**, **Centrality**, and **Exposure** to distinguish equal standing, independent reality and NPC focus, and vulnerability to external causes from HUMAN authorship.
* Added **Execution → Turn** for flexible response scope and natural handoff without authoring USER participation.
* Extended **Execution → Adaptation** to encompass narrative conventions.
* Clarified **WORLD → Continuity** to track objective physiological needs and advance fictional time by event and process duration rather than response count.
* Preserved **HUMAN**, **NPCS**, **WRITING**, and all other governing specifications unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Writing Format Governance Refinement

* Clarified the **Writing** governing sentence to strictly follow the **Header schema** and **Text forms formatting requirements** while applying Narrative craft specifications.
* Preserved every Header, Text forms, and Narrative craft row unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Writing Principle Terminology

* Refined the **Writing** governing principle to distinguish **Narrative craft specifications** from required **Header and Text forms constraints**.
* Left every other prompt rule unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Header Row Ordering

* Reordered **Writing → Header** to **Snapshot → Format → Placement → Travel** for readability, without changing any rule text or behavior.
{% endupdate %}

{% update date="2026-10-12" %}
## Writing Governance and Header Placement

* Revised the **Writing** governing principle to distinguish flexible **Narrative craft** from required **Header** and **Text forms** specifications.
* Added **Header → Placement** to put a World State header on the first line of every RP response and at the start of each new scene, while omitting headers for OOC requests.
* Preserved the existing **Snapshot**, **Format**, **Travel**, scene-break, and all other framework rules unchanged.
{% endupdate %}

{% update date="2026-10-12" %}
## Conditional Wording and Scene Break Refinement

* Refined conditional language across **World → Continuity and Consequence**, **NPCs → Conduct, Relationship, and Life course**, and **Writing → Scale & pace, Depiction, and Voice & diction**.
* Clarified **Organization & flow** separators as distinct breaks between passages, including scene cuts, viewpoint shifts, time skips, travel, and concurrent-scene transitions.
* Left the top-level **Writing** principle and **Header** rules unchanged pending further review.
{% endupdate %}

{% update date="2026-10-10" %}
## Dialogue Expression Refinement

* Refined **Writing → Voice & diction** to encourage context-fitting dialogue expression through capitalization, bold, italics, punctuation, volume, tone, and speech flow, including pauses, hesitation, interruptions, abrupt cutoffs, and trailing off.
* Distinguished ordinary dialogue punctuation from expressive symbols such as `~`, `♡`, `♥`, `♪`, and `♫` without requiring their use.
* Preserved all other Writing rules and framework kernels unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Causality Rule Refinement

* Reworked **World → Causality** around changes to objective reality, grounded in prior conditions, actual causal processes, and established world regularities.
* Consolidated enabling conditions, constraints, resistance, interference, and competing influences into a clearer operating principle.
* Retained causally bounded chance, unsuccessful or negligible effects, and outcomes assessed by their actual nature, extent, and causal contribution rather than intention or mere association.
* Left **Continuity**, **Consequence**, **Information**, **Development**, and the other kernels unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Consequence Rule Refinement

* Replaced the overly compressed **World → Consequence** wording with a fuller causal-effects principle.
* Clarified propagation through actual connections, delayed effects, accumulation, interaction, feedback, and changes to conditions, resources, and future possibilities.
* Preserved persistence, diminishment, cessation, and causally limited repairs and reversals without automatic historical resets. All other prompt rules remain unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Consequence Principle Refinement

* Simplified **World → Consequence** from a detailed catalogue into a concise rule for causally supported propagation, interaction, accumulation, persistence, diminishment, and cessation.
* Preserved causal limits on later changes and reversals without automatically undoing other effects or settled history.
* Removed redundant World State commitment and narrative-significance wording; **Continuity**, **Causality**, **Development**, and all other rules remain unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Text Forms Simplification

* Reduced **NPC thought** to its single-backtick formatting convention; existing **Viewpoint & disclosure** and **Selection & emphasis** retain responsibility for when interior thoughts appear.
* Reduced **Diegetic text** to single quotation marks, removing the additional blockquote and spoken-reading conventions.
* Preserved **NPC Cognition** and all other simulation and Writing rules unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Writing Kernel Simplification

* Removed the standalone **Speech typography** and **Cinematic scenes** groups and their six detailed functions.
* Added a concise **Voice & diction** allowance for context-fitting dialogue emphasis, restraint, softness, and expressive typography.
* Added a short **Organization & flow** convention for optional `---` scene cuts, viewpoint shifts, and transitions between distinct or concurrent scenes.
* Removed mandatory opening and closing separators and the compulsory header–passage sequence, while leaving **Header**, **Text forms**, and all other framework rules unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## World Continuity Refinement

* Reworked **World → Continuity** around a canonical, persistent World State consistent with settled history.
* Retained comprehensive objective-state persistence, including bodily and material conditions, spatial relations, and ongoing processes, while simplifying the inventory.
* Strengthened autonomous progression of ongoing activity and concurrent developments without restricting offstage simulation to a prescribed granularity.
* Preserved causal constraints and the rule for establishing compatible, previously unset objective details into World State.
{% endupdate %}

{% update date="2026-10-10" %}
## Information Access & Knowledge Ownership

* Refined **World → Information** to govern evidence and supported access paths without limiting recipients to people or groups or repeating other kernels' responsibilities.
* Explicitly included **knowledge** in **NPC Cognition** while preserving each NPC's evidence-bounded perspective.
* Placed the USER's **knowledge** under **Human → Private experience**, rather than **Personal definition**, preserving Human authorship of private states.
* Kept surrounding simulation rules and established information boundaries unchanged.
{% endupdate %}

{% update date="2026-10-10" %}
## Human Control Notation Relocation

* Moved **OOC** and **Bracketed directions** from **CORE → Human Controls** into **HUMAN → Control notation**, placed between **Input** and **USER Authorship**.
* Separated each notation's Human input convention from the Engine's corresponding responsibility, preserving the existing outside-fiction and silent-direction behaviors.
* Kept CORE focused on simulation and execution, with the existing Human and USER authorship principles unchanged.
{% endupdate %}

{% update date="2026-10-08" %}
## Expressive Typography Symbols

* Extended **Speech typography → Expressive marks** with the outline heart `♡` and musical notes `♪` and `♫`, alongside the existing filled heart `♥`.
* Preserved contextual use without fixed meanings or habitual decoration.
{% endupdate %}

{% update date="2026-10-08" %}
## Framework Terminology & Clarity

### Domain-Specific Language

* Reviewed the complete USE prompt and replaced broad **resolve** and **determine** wording with verbs specific to each function's responsibility, including **govern**, **handle**, **establish**, **derive**, **integrate**, **ground**, **model**, and **render**.
* Clarified Human authorship boundaries and the ownership of externally contingent outcomes, World causality and continuity, NPC cognition and behavior, and Writing's presentation role.
* Reworded **Personhood** to integrate NPC faculties, simplified **Volition**'s retained-goal wording, and refined **Header → Snapshot** to establish required unset values through World.
* Preserved existing kernel structure, world-state constraints, independent NPC lives, cinematic framing, dialogue typography, and text-form conventions.
{% endupdate %}

{% update date="2026-10-08" %}
## NPC Personhood & Relationships

### Personhood

* Renamed the governing **Personal continuity** principle to **Personhood**, preserving the existing integrated NPC continuity requirements.

### Individuality

* Refined **Individuality** to emphasize each NPC as a distinct, interconnected whole grounded in established evidence and lived history, without moving ownership of other NPC domains.

### Relationship

* Reworked **Relationship** to encompass established ties, roles, and statuses alongside open-ended, person-specific relational concepts.
* Distinguished established connections from individual relational perspectives, allowing concepts to coexist, reinforce, conflict, and differ across participants and domains.
* Preserved experience-grounded evolution, persistence, and different rates of change while removing blanket exclusions of numerical systems, labels, and roles.
{% endupdate %}

{% update date="2026-10-08" %}
## Direct Vocal Sound Rendering

### Writing: Depiction

* Refined **Depiction** to render vocalizations as readable audible sounds instead of merely narrating that they occurred.
* Kept onomatopoeia faithful to the sound actually produced, with delivery and physical causes resolved by the owning simulation domains.
* Preserved accompanying narration and the existing **Text forms → Dialogue & vocal** quotation convention without prescribing stock vocalizations or mandatory styles.
{% endupdate %}

{% update date="2026-10-08" %}
## Independent NPC Lives & World Dynamics

### NPC Life Course

* Replaced **Life progression** with **Life course**, shifting the focus from re-entry and offstage management to each NPC's independently unfolding life.
* Integrated everyday rhythms, longer-term trajectories, roles, relationships, commitments, pursuits, and circumstances as interacting aspects of a continuing life.
* Preserved stability, emergence, change, endings, different rates of change, and the accumulated effects of lived experience on future possibilities.
* Aligned the NPC **Personal continuity** overview with the new function name.

### NPC Communication

* Generalized multiparty interaction using **interaction dynamics to vary**, supporting different speaking patterns, changing participation, and social dynamics without privileging NPC-to-NPC exchanges or imposing turn quotas.

### World Development

* Clarified that autonomous developments can **gain or lose momentum**, without mandatory escalation, conflict, or activity.

### Temporal Language

* Replaced all six instances of **in-world time** with context-appropriate references to time or removed the unnecessary qualifier.
* Preserved World continuity, NPC Volition, and header snapshot semantics while simplifying their wording.
{% endupdate %}

{% update date="2026-10-08" %}
## Cinematic Scenes & Expressive Dialogue

### Cinematic Scenes

* Added **Cinematic scenes** with **Framing**, **Cuts**, and **Interleaving**.
* Standardized header-framed narrative passages with `---` dividers, optional additional passages, and a required final divider for every RP output.
* Enabled flexible narrative cuts among selected moments, subjects, and developments when a distinct passage is warranted.
* Supported interleaved concurrent scenes and returns to earlier threads while preserving their individual causal and temporal continuity.

### Headers & Travel

* Kept header snapshots grounded in the actual World State at the starting time and location of each passage.
* Made in-progress travel headers apply to any traveler, including distant NPCs: show `Origin → Destination` when established, or the actual route or position otherwise.
* Removed the earlier USER-specific travel phrasing and separate automatic travel-boundary rule.

### Sounds & Speech

* Refined **Depiction** to give sounds direct audible form, render vocalizations readably, and fit onomatopoeia to its source and physical qualities.
* Added **Speech typography → Vocal emphasis** for expressive capitalization, bold, italics, and combinations shaped by actual delivery.
* Added **Speech typography → Speech flow** for pauses, interruptions, restarts, trailing speech, and prolongation.
* Added **Speech typography → Expressive marks** for context-appropriate punctuation and stylization, including `?!`, `!!!`, `~`, and `♥`.

### Design

* Preserved the existing **Viewpoint & disclosure**, **NPC Communication**, and **Text forms** responsibilities instead of adding a separate dialogue simulation subsystem.
* Kept cinematic cuts, additional passages, and expressive typography context-driven rather than mandatory.
{% endupdate %}

{% update date="2026-10-07" %}
## Framework & Documentation Update

### Core

* Added **Adaptation** for genre, era, tone, setup, context, AI model, world type, supporting systems, modules, and custom instructions.
* Added **Human Controls** with two conventions: **OOC:** suspends roleplay for an outside-fiction response; **\[directions]** applies instructions silently during roleplay.

### Human

* Separated **authority binding** in the governing principle from **cross-domain application** in the Human input resolution.
* Preserved semantically distinct contributions, meaning-defining relationships, stated scope, every USER-owned variable, and explicit scoped delegation.
* Kept the detailed USER Authorship domains intact.

### Chat Memory

* Replaced the earlier engine-specific compaction with a reusable chat-memory prompt and explicit Markdown template.
* Organized memory into **World**, chronological **History**, per-character records, **Current State**, **Unresolved**, **Last Exchange**, and optional **Gaps**.
* Retained character development, directional relationships, knowledge, beliefs, secrets, ongoing consequences, and the final continuation boundary.
* Removed repeated instruction, writing, baseline definition, and voice sections.
* Aligned the Compaction prompt with the **OOC:** convention and shortened its usage guide.

### Documentation

* Organized navigation into **Overview**, **Setup**, **Chat Tools**, and **Updates**.
* Shortened page titles, added the Compaction icon, repaired overview links, and removed duplicated compaction content.
* Removed the empty **Extra Modules**, **Nano Prompt**, and **Prefill** pages.
* Added a concise Overview introduction and clearly labeled the Discord discussion and direct-message contact.

### Generation Settings

* Set **Temperature** to **1.0**.
* Set **Top K**, **Top P**, **Repetition Penalty**, and **Frequency Penalty** to **0**.
* Set **Max Tokens** to **0 (On Janitor) OR Maximum**.
* Retained **32k** as the practical context minimum, with the largest supported context recommended.
{% endupdate %}
{% endupdates %}
