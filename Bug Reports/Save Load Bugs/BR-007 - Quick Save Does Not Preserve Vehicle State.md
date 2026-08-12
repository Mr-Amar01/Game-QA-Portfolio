# BR-007 – Quick Save Does Not Preserve Vehicle State

> **Portfolio Note:** Fictional QA portfolio example created for demonstration of save/load testing.

## Game
Cyberpunk 2077

## Platform
PC

## Category
Save / Load / Vehicles

## Severity
Major

## Priority
High

## Frequency
2/5

## Description
A quick save created while the player is interacting with a vehicle can restore the player at the correct location but with the previous vehicle state instead of the state present when the save was created.

## Preconditions
- Player has access to a vehicle.
- Quick save functionality is available.

## Steps to Reproduce
1. Enter a vehicle.
2. Move the vehicle to a distinct location.
3. Create a quick save while the vehicle is present.
4. Exit to the main menu.
5. Load the quick save.
6. Observe the player and vehicle state.

## Expected Result
The loaded game restores the player and relevant vehicle state consistently with the save point.

## Actual Result
The player can load successfully but the vehicle state does not always match the state at the time of saving.

## Impact
Unexpected state restoration can affect gameplay continuity and player confidence in save reliability.

## Suggested Verification
Repeat with manual saves, autosaves, different vehicles, and saves created before/after entering the vehicle.