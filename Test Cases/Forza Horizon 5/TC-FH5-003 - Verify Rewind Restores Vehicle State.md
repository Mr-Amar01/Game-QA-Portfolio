# TC-FH5-003 – Verify Rewind Restores Vehicle State

## Module
Rewind / Vehicle Physics

## Type
Functional

## Priority
High

## Objective
Verify that rewind restores the vehicle to the selected point with the correct position, orientation and relevant driving state.

## Preconditions
- Rewind feature enabled.
- Vehicle is moving.

## Steps
1. Drive through a short sequence of turns.
2. Trigger a collision or braking event.
3. Activate rewind.
4. Select a point before the event.
5. Resume driving.
6. Compare the restored state with the selected point.

## Expected Result
Vehicle state matches the selected rewind point consistently.

## Pass Criteria
No unexpected position, orientation or physics state is introduced.