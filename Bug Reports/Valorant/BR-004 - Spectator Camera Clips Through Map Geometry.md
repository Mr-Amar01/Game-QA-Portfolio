# BR-004 – Spectator Camera Clips Through Map Geometry

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
Spectator / Graphics

## Severity
Medium

## Priority
Medium

## Description
The spectator camera can move close enough to map geometry to partially clip through the environment and expose unintended geometry.

## Preconditions
- Player is eliminated.
- Spectator mode is available.

## Steps to Reproduce
1. Enter a match.
2. Become eliminated.
3. Enter spectator mode.
4. Cycle between available observation targets.
5. Move or rotate the spectator camera toward nearby geometry.

## Expected Result
The spectator camera remains within intended camera boundaries and does not expose unintended geometry.

## Actual Result
The camera can partially clip through map geometry.

## Impact
Creates a visual defect and may expose unintended map areas.

## Reproduction Rate
3/5