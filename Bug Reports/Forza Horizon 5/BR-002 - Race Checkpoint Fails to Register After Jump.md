# BR-002 – Race Checkpoint Fails to Register After Jump

> Portfolio example for QA demonstration.

## Game
Forza Horizon 5

## Platform
PC

## Category
Race Logic / Checkpoints

## Severity
High

## Priority
High

## Frequency
2/5

## Description
A race checkpoint may fail to register when the vehicle crosses its trigger volume while airborne after a jump.

## Preconditions
- Race with checkpoint markers.
- Vehicle approaches a checkpoint at high speed.
- Jump or elevation change exists near the checkpoint.

## Steps to Reproduce
1. Start the race.
2. Approach the affected checkpoint at high speed.
3. Take the jump near the checkpoint.
4. Cross the checkpoint trigger while airborne.
5. Continue driving.

## Expected Result
The checkpoint registers when the vehicle validly crosses its trigger volume.

## Actual Result
The checkpoint can remain incomplete, causing the route to direct the player back toward the checkpoint.

## Impact
Can disrupt race progression and increase completion time.

## Reproduction Rate
2/5