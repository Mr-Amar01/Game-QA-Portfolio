# BR-007 – Crosshair Preset Not Applied After Profile Switch

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
Settings / UI

## Severity
Low

## Priority
Medium

## Description
Switching to a saved crosshair profile can leave the displayed crosshair unchanged until the player enters another menu or reloads the profile.

## Preconditions
- At least two saved crosshair configurations.

## Steps to Reproduce
1. Open crosshair settings.
2. Save two distinct crosshair configurations.
3. Apply profile A.
4. Switch to profile B.
5. Return to gameplay.

## Expected Result
Profile B is immediately applied and displayed in gameplay.

## Actual Result
The previous crosshair can remain visible until another settings interaction refreshes the state.

## Impact
Player settings are not reflected immediately and can affect aiming consistency.

## Reproduction Rate
3/5