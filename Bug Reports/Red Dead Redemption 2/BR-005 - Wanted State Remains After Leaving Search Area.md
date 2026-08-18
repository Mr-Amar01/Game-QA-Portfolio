# BR-005 – Wanted State Remains After Leaving Search Area

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
Law / World State

## Severity
Medium

## Priority
Medium

## Reproduction Rate
2/5

## Description
After the player leaves the designated search area and meets the conditions for clearing the wanted state, the alert indicator can remain active longer than expected.

## Preconditions
- Player has an active wanted/search state.
- Player can leave the search area.

## Steps to Reproduce
1. Trigger a wanted state.
2. Leave the search area without being detected.
3. Remain outside the search area for the required duration.
4. Observe the wanted indicator.

## Expected Result
The wanted state updates according to the configured world-state rules.

## Actual Result
The indicator may remain active after the player has met the expected clear conditions.

## Impact
Can prevent normal free-roam activities and create inconsistent world-state feedback.