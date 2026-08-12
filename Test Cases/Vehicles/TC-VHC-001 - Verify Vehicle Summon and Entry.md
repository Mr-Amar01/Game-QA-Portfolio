# TC-VHC-001 – Verify Vehicle Summon and Entry

> Portfolio test case for demonstrating vehicle-system functional coverage.

## Module
Vehicles

## Type
Functional

## Priority
High

## Objective
Verify that a player-owned vehicle can be summoned and entered from a valid location.

## Preconditions
- Player owns or has access to a summonable vehicle.
- Player is in an area where vehicle spawning is permitted.
- Player is not inside a restricted mission state.

## Test Steps
1. Open the vehicle summon interface.
2. Select an available vehicle.
3. Wait for the vehicle to arrive.
4. Approach the vehicle.
5. Use the interaction prompt to enter.
6. Drive a short distance.
7. Exit the vehicle.

## Expected Result
Vehicle arrives at a valid location, interaction becomes available, player enters successfully, vehicle responds to driving input, and player can exit normally.

## Pass Criteria
No missing interaction prompt, invalid spawn, blocked entry, or input failure occurs during the flow.