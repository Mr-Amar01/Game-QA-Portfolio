# TC-RDR2-003 – Verify NPC Interaction State Transitions

## Module
NPC / Animation

## Priority
Medium

## Type
Functional / Visual

## Objective
Verify that NPCs transition correctly between interaction and ambient states.

## Preconditions
- Interactable NPC is available.

## Steps
1. Approach the NPC.
2. Start an interaction.
3. Complete the interaction.
4. Move away from the NPC.
5. Observe the NPC animation and behaviour.

## Expected Result
The NPC exits the interaction state and resumes the correct ambient behaviour.

## Pass Criteria
No animation lock, frozen pose or incorrect transition persists.