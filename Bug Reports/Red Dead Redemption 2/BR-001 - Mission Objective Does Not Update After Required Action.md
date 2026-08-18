# BR-001 – Mission Objective Does Not Update After Required Action

> Portfolio example for QA demonstration. Not a claim of a production defect discovered by the author.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
Mission / Progression

## Severity
High

## Priority
High

## Reproduction Rate
3/5

## Description
After the player completes a required mission action, the objective state may fail to update and the mission remains on the previous objective.

## Preconditions
- Mission is active.
- Player has reached the relevant objective.

## Steps to Reproduce
1. Load the mission checkpoint.
2. Complete the required objective interaction.
3. Wait for the mission objective to update.
4. Observe the mission tracker and world marker.

## Expected Result
The completed objective is marked complete and the next mission objective becomes active.

## Actual Result
The previous objective remains active and progression does not continue.

## Impact
Mission progression can become blocked without restarting or reloading the checkpoint.

## Suggested Verification
Repeat after checkpoint reload, mission restart and on a clean save.