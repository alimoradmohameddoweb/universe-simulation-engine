---
description: Create a reusable checkpoint for long-running roleplay chats.
icon: compress
---

# Compaction

1. **Generate:** Send the prompt below as a user message before history is removed.
2. **Keep:** Save and reinsert the resulting checkpoint when clearing history.
3. **Update:** Supply the checkpoint and subsequent turns, then run the prompt again.

{% code title="Prompt" overflow="wrap" fullWidth="true" %}
```md
OOC:

# Chat Memory Compaction

## Task

**Compaction:** Return only a Markdown checkpoint of chat-established information needed to continue without earlier messages. Stop at the latest fictional exchange; do not continue the scene.

## Consolidation

- **Update:** Merge previous memory with subsequent turns. Preserve unaffected information; apply established changes and corrections within scope.
- **Selection:** Retain details whose loss would change continuity, characterization, available choices, or interpretation of the next exchange.
- **Precision:** Preserve attribution, chronology, uncertainty, and consequential distinctions between fact, belief, intention, attempt, and outcome.
- **History:** Order retained events from earliest to latest, using established timing or relative sequence. Keep the causes and results needed to explain current state.
- **Development:** Preserve established character changes, including departures from their initial definition. Distinguish lasting development from temporary states; retain the experience that supports the change.
- **Perspectives:** Record consequential knowledge, beliefs, misconceptions, and secrets by character, including evidence and disclosure boundaries where established.
- **Compression:** Merge repetition and summarize completed routine. Retain exact wording only when paraphrase would lose essential meaning.
- **Exclusions:** Omit discarded alternatives and the compaction request. Record material gaps without filling them.

## Format

- **Structure:** Follow the template below. Repeat the character entry for each relevant NPC and include a separate player-character entry where needed.
- **Density:** Omit empty sections and fields except **Last Exchange**. Replace placeholders with supported information; use only the detail the chat warrants.
- **Placement:** Give each fact one primary location. Use History for consequential events, character entries for their personal effects, and Current State for the immediate scene.
- **Coverage:** Identify the stopping point in Last Exchange. Add Gaps only when missing context or unresolved contradictions materially affect continuation.

**Template:**

# Chat Memory

## World

- **[Subject]:** [Relevant setting, world fact, or lasting condition.]

## History

- **[Established time or sequence]:** [Event and relevant cause → consequential result.]

## Characters

### [Name]

- **Development:** [What changed from earlier characterization, why, and whether lasting or temporary.]
- **State:** [Current condition, motives, intentions, plans, or commitments.]
- **Relationships:** [Toward whom; established stance, development, and relevant basis.]
- **Knowledge & Beliefs:** [What is known, believed, suspected, mistaken, or consequentially unknown; supporting access or evidence.]
- **Secrets:** [Content and truth status; who holds it, who knows it, and from whom it is concealed.]

## Current State

- **Time & Place:** [Established scene timing and location.]
- **Participants:** [Who is present and relevant positions.]
- **Conditions:** [Relevant physical, environmental, material, or resource state.]
- **Activity:** [What is underway, including relevant concurrent or offstage activity.]

## Unresolved

- **[Thread]:** [Current status, relevant actors, dependencies, and established timing.]

## Last Exchange

- **User:** [Latest fictional contribution.]
- **Assistant:** [Subsequent fictional response, or “Unanswered.”]
- **Boundary:** [Latest included event; what is complete, underway, unanswered, or open.]

## Gaps

- **[Issue]:** [Material missing information or unresolved contradiction.]
```
{% endcode %}
