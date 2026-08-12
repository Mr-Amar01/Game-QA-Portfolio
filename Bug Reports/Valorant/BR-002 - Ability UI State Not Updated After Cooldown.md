# BR-002 – Ability UI State Not Updated After Cooldown

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
UI / Ability System

## Severity
Medium

## Priority
Medium

## Description
The ability becomes available after its cooldown completes, but the HUD indicator continues to display the unavailable state until another UI interaction occurs.

## Preconditions
- Agent with a cooldown-based ability selected.
- Ability has entered cooldown.

## Steps to Reproduce
1. Enter a match.
2. Use the selected ability.
3. Wait until the cooldown expires.
4. Observe the ability icon immediately after cooldown completion.
5. Perform another UI interaction.

## Expected Result
The HUD immediately reflects that the ability is available.

## Actual Result
The HUD remains in the cooldown state until another UI refresh occurs.

## Impact
Players may incorrectly believe an ability is unavailable and lose gameplay opportunities.

## Reproduction Rate
4/5