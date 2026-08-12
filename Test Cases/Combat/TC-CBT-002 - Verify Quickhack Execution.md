# TC-CBT-002 – Verify Quickhack Execution

> Portfolio test case for demonstrating functional cyberware/quickhack coverage.

## Module
Combat / Quickhacks

## Type
Functional

## Priority
High

## Objective
Verify that a selected quickhack can be applied to a valid target when the required resources and conditions are available.

## Preconditions
- Player has a functioning cyberdeck.
- At least one compatible quickhack is installed.
- Target is within valid range.
- Required RAM/resource is available.

## Test Steps
1. Enter a hostile encounter.
2. Target an eligible enemy.
3. Open the quickhack interface.
4. Select a valid quickhack.
5. Confirm the quickhack.
6. Observe the target and resource values.

## Expected Result
The quickhack is applied successfully, the required resource is consumed, and the target receives the intended effect.

## Pass Criteria
Quickhack execution, target feedback, resource consumption, and cooldown/state handling are consistent with the selected ability.