# BR-005 – Rewind State Causes Incorrect Vehicle Position

> Portfolio example for QA demonstration.

## Game
Forza Horizon 5

## Platform
PC

## Category
Gameplay / Rewind

## Severity
High

## Priority
High

## Frequency
2/5

## Description
Using rewind near a collision can restore the vehicle to a position that does not accurately match the selected rewind point.

## Preconditions
- Rewind feature available.
- Vehicle moving at moderate or high speed.

## Steps to Reproduce
1. Start driving.
2. Approach a collision or sudden change in direction.
3. Activate rewind.
4. Select a point immediately before the event.
5. Resume driving.
6. Compare the restored vehicle position with the selected point.

## Expected Result
Vehicle position, orientation and relevant physics state match the selected rewind point.

## Actual Result
The restored vehicle state can differ from the selected point.

## Impact
May affect driving consistency and race outcomes.

## Reproduction Rate
2/5