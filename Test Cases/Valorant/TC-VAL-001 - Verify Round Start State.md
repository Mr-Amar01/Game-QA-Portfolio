# TC-VAL-001 – Verify Round Start State

> Portfolio test case for QA demonstration.

## Module
Match Flow

## Priority
High

## Type
Functional

## Objective
Verify that every round starts with the correct player, economy, ability and HUD state.

## Preconditions
- Match has started.
- Player can reach a new round.

## Steps
1. Complete a round.
2. Observe the transition to the next round.
3. Check player health and available abilities.
4. Check weapon/equipment state.
5. Check relevant HUD values.

## Expected Result
All round-reset states are applied correctly and the HUD matches the authoritative round state.

## Pass Criteria
No previous-round state persists into the new round.