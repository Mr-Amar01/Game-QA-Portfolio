# TC-VAL-004 – Verify Spectator Camera Boundaries

## Module
Spectator Mode / Graphics

## Priority
Medium

## Type
Boundary / Visual

## Objective
Verify that spectator camera movement remains within intended camera boundaries and does not expose unintended geometry.

## Preconditions
- Player is eliminated.
- Spectator mode is available.

## Steps
1. Enter spectator mode.
2. Cycle through available players.
3. Move the spectator camera toward walls, floors and map edges where permitted.
4. Observe camera clipping and exposed geometry.

## Expected Result
Camera movement remains within designed limits and environmental geometry renders correctly.

## Pass Criteria
No unintended map exposure or camera clipping occurs.