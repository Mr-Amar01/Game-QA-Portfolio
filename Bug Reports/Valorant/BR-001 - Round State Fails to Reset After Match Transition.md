# BR-001 – Round State Fails to Reset After Match Transition

> Portfolio example for QA demonstration. Not a claim of a production defect discovered by the author.

## Game
VALORANT

## Platform
PC

## Category
Match Flow / Round State

## Severity
High

## Priority
High

## Frequency
3/5

## Description
A player state from the previous round remains incorrectly applied after the next round begins, resulting in inconsistent gameplay state.

## Preconditions
- Custom match or test environment available.
- Player has completed at least one round.

## Steps to Reproduce
1. Start a match.
2. Complete a round while carrying a temporary gameplay state.
3. Allow the next round to begin.
4. Observe the player's state and related HUD elements.

## Expected Result
The new round starts with the correct round-reset state and HUD values.

## Actual Result
A previous-round state or HUD value remains active after the new round starts.

## Impact
Can create an unfair gameplay state and may affect round integrity.

## Reproduction Rate
3/5

## Suggested Verification
Repeat across multiple rounds and verify after reconnecting or observing the next-round transition.