---
description: Consolidated framework and documentation changes.
icon: clock-rotate-left
---

# Changelog

{% updates format="full" %}
{% update date="2026-11-13" %}
## FRAMEWORK — Composition, Canonical State, and Expression Restructure

Removed the `<FRAMEWORK>` XML wrapper; Replaced By `<RUNTIME>`.

#### Structure

* Renamed **SIMULATION → Setting** to **SIMULATION → Composition** and updated **Architecture** and **Ownership** accordingly (world's contents, populations, and operating laws).
* Restructured **PRESENTATION** from four groups (**Output**, **Composition & Style**, **Header**, **Text forms**) into one consolidated **Expression & Style** group.
* Removed **Output → Rendering**; rendering is now implied by **Expression & Style → General Style**.

#### Mechanics

* Added a **Canonical State** grouping under **Mechanics**, co-locating **Continuity** with the new **World State Ledger** function.
* Moved the full **Header** specification (Snapshot, Format, Placement, Travel) from **PRESENTATION** into **Mechanics → Canonical State → World State Ledger**, now with emoji field markers (🕒 📅 🌤️ 📍) replacing bracketed labels.
* Updated **Continuity**'s open-details clause from “emerge through Development” to “emerge through Evolution.”

#### Evolution

* Split **Evolution → Development** into **Evolution → Universe** (environments, populations, institutions, systems, events) and **Evolution → Inhabitants** (non-USER lives, routines, relationships, aging, growth, setbacks, trajectories).

#### Entities

* Moved **Volition** from **Agency** into **Mind**; **Agency** now contains only **Conduct**.
* Expanded **Individuality** with personal history, accumulated life experiences, and identity continuity feeding into self-understanding.
* Removed the standalone **Agents → Life → Life course** function; its content now lives in **Evolution → Inhabitants** (ongoing development) and **Individuality** (identity state).

#### Presentation

* Added **General Style**, defining overall writing style and quality standards (High-quality / Literary / Clean-prose / Graphical / Vivid / Rich / Sensory / Observable / Explicit / Dynamic / Uncensored).
* Renamed **Explicitness & implication** to **Directness & implication**; reworded Apply from “Balance” to “Dynamically balance.”
* Restructured **Depiction** into **General / Physical / Auditory** sub-functions with **Avoid** consolidated.
* Removed expressive-symbol guidance from **Voice & diction**; symbols now live under **Textual Conventions → Typography**.
* Consolidated **Text forms** into **Textual Conventions** (Narration, Dialogue & vocals, Agent thoughts, Onomatopoeia, Typography); removed the separate **Diegetic text** convention.
* Added a compatibility clause to **Agent thoughts**: backticks remain primary “unless using a different established format,” so bot-card greetings that use bold or emoji for thoughts are not overwritten.
* Trimmed **Scale & pace** Apply (“keeping elapsed world time distinct from textual length”) and Avoid (“advancing to future events solely because they are mentioned”); both are now model-specific concerns rather than universal rules.

Preserved all Causality, Consequence, and Information mechanics; USER authorship boundaries; Agent Cognition, Emotion, Motivation, Conduct, Relationship, and Communication; and the remaining style guidance.
{% endupdate %}
{% endupdates %}
