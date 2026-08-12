# TC-CBT-001 – Verify Weapon Firing and Reload Flow

> Portfolio test case for demonstrating functional combat coverage.

## Module
Combat / Weapons

## Type
Functional

## Priority
High

## Objective
Verify that a usable ranged weapon can fire, consume ammunition, enter the reload state, and return to a ready-to-fire state.

## Preconditions
- Player has a ranged weapon equipped.
- Weapon has ammunition in reserve.
- Player is outside a cutscene or restricted interaction.

## Test Steps
1. Equip the weapon.
2. Aim at a valid target area.
3. Fire until the magazine is empty.
4. Observe the weapon state.
5. Reload.
6. Fire again.

## Expected Result
- Weapon fires correctly while ammunition is available.
- Magazine count decreases appropriately.
- Reload begins when requested.
- Reload completes successfully when reserve ammunition exists.
- Weapon can fire again after reload.

## Pass Criteria
No incorrect ammunition counts, blocked reload states, or loss of input occurs during the sequence.