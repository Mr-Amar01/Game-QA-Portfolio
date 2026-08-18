# BR-004 – Weapon Wheel Selection Persists After Closing Menu

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
UI / Weapon System

## Severity
Medium

## Priority
Medium

## Reproduction Rate
3/5

## Description
The weapon wheel can display a previously selected slot after the player closes and reopens it, despite the equipped weapon state having changed.

## Preconditions
- Player has multiple weapons available.

## Steps to Reproduce
1. Open the weapon wheel.
2. Select a weapon from one slot.
3. Close the weapon wheel.
4. Change the equipped weapon through gameplay.
5. Reopen the weapon wheel.
6. Observe the selection indicator.

## Expected Result
The weapon wheel accurately reflects the player's current equipped weapon.

## Actual Result
The selection indicator may display stale information.

## Impact
Can cause incorrect player feedback and unintended weapon selection.