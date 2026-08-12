# TC-SAV-001 – Verify Manual Save and Load State

> Portfolio test case for demonstrating save/load reliability coverage.

## Module
Save & Load

## Type
Functional / Data Integrity

## Priority
Critical

## Objective
Verify that a manually saved game restores the expected player progression and gameplay state when loaded.

## Preconditions
- Player has a valid save slot.
- Player has changed a measurable gameplay state such as location, equipment, or quest progress.

## Test Steps
1. Load a valid save.
2. Record the current location and relevant gameplay state.
3. Make a controlled change to the gameplay state.
4. Create a manual save in a new slot.
5. Return to the main menu.
6. Load the newly created save.
7. Compare the loaded state with the state recorded at save time.

## Expected Result
The saved game loads successfully and restores the player to the expected location and gameplay state without corruption, duplication, or unexpected progression changes.

## Pass Criteria
All relevant persistent state matches the state captured when the manual save was created.