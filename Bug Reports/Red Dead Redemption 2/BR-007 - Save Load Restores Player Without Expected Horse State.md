# BR-007 – Save/Load Restores Player Without Expected Horse State

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
Save / Load / Persistence

## Severity
High

## Priority
High

## Reproduction Rate
2/5

## Description
After loading a save created while the player's horse was in a specific gameplay state, the player state can be restored while the associated horse state is not restored as expected.

## Preconditions
- Player has an active horse.
- Horse is present in the world.
- Manual save is available.

## Steps to Reproduce
1. Enter a controlled area with the horse.
2. Create a manual save.
3. Change the horse's position or gameplay state.
4. Load the manual save.
5. Observe the player and horse states.

## Expected Result
The relevant persisted player and horse states are restored consistently with the save point.

## Actual Result
The horse state may differ from the state represented by the loaded save.

## Impact
Can cause progression, traversal or gameplay-state inconsistencies.