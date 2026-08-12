# BR-003 – Vehicle Audio Persists After Vehicle Switch

> Portfolio example for QA demonstration.

## Game
Forza Horizon 5

## Platform
PC

## Category
Audio / Vehicle System

## Severity
Medium

## Priority
Medium

## Frequency
3/5

## Description
After switching vehicles, an audio layer associated with the previous vehicle can remain audible briefly instead of transitioning cleanly to the new vehicle's audio profile.

## Preconditions
- Player owns multiple vehicles.
- Audio output is enabled.

## Steps to Reproduce
1. Enter a vehicle.
2. Drive for several seconds.
3. Open the vehicle switch or garage flow.
4. Select a different vehicle.
5. Return to gameplay.
6. Observe engine and vehicle audio.

## Expected Result
The previous vehicle audio stops and the new vehicle's audio profile is played correctly.

## Actual Result
An audio layer from the previous vehicle can persist during the transition.

## Impact
Creates an audio inconsistency and reduces immersion.

## Reproduction Rate
3/5