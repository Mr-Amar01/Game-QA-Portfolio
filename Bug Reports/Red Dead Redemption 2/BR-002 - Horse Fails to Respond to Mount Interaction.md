# BR-002 – Horse Fails to Respond to Mount Interaction

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
Horse / Interaction

## Severity
Medium

## Priority
High

## Reproduction Rate
3/5

## Description
The mount interaction prompt can appear while the horse does not respond to the interaction input.

## Preconditions
- Player owns or has access to a horse.
- Horse is stationary and within interaction range.

## Steps to Reproduce
1. Approach the horse.
2. Wait for the mount interaction prompt.
3. Press the mount input.
4. Observe the player and horse state.

## Expected Result
The player mounts the horse and control is transferred to the mounted state.

## Actual Result
The prompt is displayed but the interaction may fail to trigger.

## Impact
Can interrupt traversal and delay mission or exploration activities.

## Suggested Verification
Repeat from different approach angles and after dismounting and remounting.