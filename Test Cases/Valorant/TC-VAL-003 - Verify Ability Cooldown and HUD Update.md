# TC-VAL-003 – Verify Ability Cooldown and HUD Update

## Module
Ability System / UI

## Priority
High

## Type
Functional

## Objective
Verify that an ability enters cooldown correctly and becomes available immediately after the cooldown expires.

## Preconditions
- Agent with a cooldown-based ability.
- Ability is available.

## Steps
1. Use the ability.
2. Observe the ability HUD indicator.
3. Confirm cooldown begins.
4. Wait for the cooldown to expire.
5. Observe the HUD.
6. Attempt to use the ability again.

## Expected Result
Cooldown begins correctly, HUD reflects the cooldown, and the ability becomes usable immediately when the timer expires.

## Pass Criteria
No delay or stale HUD state prevents ability usage.