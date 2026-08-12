# BR-004 – Texture LOD Fails To Update After Fast Travel

> **Portfolio Note:** Fictional QA portfolio example created for portfolio demonstration.

## Game
Cyberpunk 2077

## Platform
PC

## Category
Graphics / Texture Streaming

## Severity
Minor

## Priority
Medium

## Frequency
3/5

## Description
Some environmental textures remain at a visibly lower level of detail for an extended period after fast travelling into a dense area.

## Preconditions
- Fast travel is available.
- Player has a save located in a dense city environment.
- Texture streaming is enabled.

## Steps to Reproduce
1. Start from a location with normal texture quality.
2. Fast travel to a dense city district.
3. Immediately move toward buildings and large environmental assets.
4. Observe texture quality during the first several seconds after arrival.

## Expected Result
Textures transition to the intended level of detail as the player approaches the assets.

## Actual Result
One or more assets can remain visibly low resolution longer than expected before updating.

## Impact
Temporary visual quality degradation is noticeable during traversal and can reduce presentation quality.

## Suggested Verification
Repeat after cold boot, warm restart, different graphics presets, and different streaming/storage configurations.