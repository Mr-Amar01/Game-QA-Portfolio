# BR-001 – Vehicle Respawn Places Car Outside Intended Race Route

> Portfolio example for QA demonstration. Not a claim of a production defect discovered by the author.

## Game
Forza Horizon 5

## Platform
PC

## Category
Gameplay / Vehicle Respawn

## Severity
High

## Priority
High

## Frequency
3/5

## Description
After a vehicle leaves the drivable area during a race, the respawn system can place the vehicle at an unintended position that gives an inconsistent race state.

## Preconditions
- Active race event.
- Vehicle can leave the intended route.

## Steps to Reproduce
1. Start a race.
2. Deliberately drive outside the intended route.
3. Continue until the automatic rewind or respawn system activates.
4. Observe the vehicle position after recovery.

## Expected Result
The vehicle is returned to a safe position on the intended route without providing an unintended advantage or disadvantage.

## Actual Result
The vehicle may be restored at an inconsistent position relative to the race route.

## Impact
Can affect race fairness and checkpoint progression.

## Reproduction Rate
3/5