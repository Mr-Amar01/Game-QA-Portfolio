# TC-VAL-002 – Verify Weapon Pickup Interaction

## Module
Weapons / Interaction

## Priority
Medium

## Type
Functional

## Objective
Verify that a player can correctly pick up an available weapon and that the HUD updates.

## Preconditions
- A valid weapon is available for pickup.
- Player is within interaction range.

## Steps
1. Approach the dropped weapon.
2. Observe the interaction prompt.
3. Pick up the weapon.
4. Observe the equipped weapon and HUD.

## Expected Result
The weapon is picked up, the correct weapon is equipped, and the HUD reflects the new weapon state.

## Pass Criteria
No stale interaction prompt remains after pickup.