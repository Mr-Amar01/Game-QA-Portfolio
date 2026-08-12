# BR-003 – Weapon Pickup Prompt Persists After Weapon Is Removed

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
Interaction / UI

## Severity
Low

## Priority
Low

## Description
A weapon interaction prompt remains visible briefly after the weapon is no longer present at the interaction location.

## Preconditions
- Weapon is available for pickup.
- Player is within interaction range.

## Steps to Reproduce
1. Approach a dropped weapon.
2. Observe the pickup prompt.
3. Have another player pick up the weapon.
4. Immediately observe the same location.

## Expected Result
The pickup prompt disappears when the weapon is removed.

## Actual Result
The prompt remains visible temporarily despite no weapon being available.

## Impact
Can cause misleading interaction feedback.

## Reproduction Rate
4/5