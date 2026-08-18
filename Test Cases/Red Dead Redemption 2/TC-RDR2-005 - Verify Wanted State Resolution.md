# TC-RDR2-005 – Verify Wanted State Resolution

## Module
Law / World State

## Priority
High

## Type
Functional / State Validation

## Objective
Verify that the wanted state transitions correctly when the player leaves the search area and satisfies the required conditions.

## Preconditions
- Wanted/search state can be triggered.

## Steps
1. Trigger a wanted state.
2. Move away from the search area.
3. Avoid detection according to the scenario conditions.
4. Wait for the search state to resolve.
5. Observe the HUD and world behaviour.

## Expected Result
The wanted state changes according to the defined rules and the HUD reflects the current state.

## Pass Criteria
No stale wanted indicator or incorrect law-enforcement state remains.