# TC-RDR2-007 – Verify Save and Load Persistence for Player and Horse State

## Module
Save / Load / Persistence

## Priority
High

## Type
Functional / Persistence

## Objective
Verify that relevant player and horse states are restored consistently after loading a manual save.

## Preconditions
- Player has an active horse.
- Manual save functionality is available.

## Steps
1. Enter a controlled location with the horse.
2. Record relevant player and horse state.
3. Create a manual save.
4. Make controlled changes to player and horse state.
5. Load the manual save.
6. Compare the restored state with the saved state.

## Expected Result
The saved player and horse states are restored consistently.

## Pass Criteria
No unexpected state loss, duplication or mismatch occurs after loading.