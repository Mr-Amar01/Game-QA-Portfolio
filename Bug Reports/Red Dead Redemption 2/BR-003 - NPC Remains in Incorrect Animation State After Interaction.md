# BR-003 – NPC Remains in Incorrect Animation State After Interaction

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
NPC / Animation

## Severity
Low

## Priority
Medium

## Reproduction Rate
3/5

## Description
An NPC can remain in an incorrect animation state for several seconds after a completed interaction.

## Preconditions
- NPC is available for interaction.
- Player is within interaction range.

## Steps to Reproduce
1. Approach the NPC.
2. Start and complete the interaction.
3. Move a short distance away.
4. Observe the NPC animation state.

## Expected Result
The NPC transitions cleanly to the appropriate ambient or gameplay animation.

## Actual Result
The NPC can briefly remain in an interaction animation or transition incorrectly.

## Impact
Creates a visible presentation defect and may indicate an animation-state transition issue.