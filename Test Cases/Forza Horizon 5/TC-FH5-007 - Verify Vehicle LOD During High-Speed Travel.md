# TC-FH5-007 – Verify Vehicle LOD During High-Speed Travel

## Module
Graphics / Asset Streaming

## Type
Visual / Performance

## Priority
Medium

## Objective
Verify that vehicle geometry and textures transition between LOD levels smoothly during high-speed movement.

## Preconditions
- Detailed vehicle available.
- High-speed driving area available.

## Steps
1. Select a vehicle with detailed exterior geometry.
2. Drive at low speed and observe the vehicle.
3. Increase speed significantly.
4. Rotate the camera around the vehicle.
5. Repeat in multiple environments.

## Expected Result
LOD transitions remain visually smooth without noticeable popping, missing geometry or severe texture degradation.

## Pass Criteria
No distracting LOD artifacts are observed during normal high-speed travel.