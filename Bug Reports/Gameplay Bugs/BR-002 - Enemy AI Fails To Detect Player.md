# BR-002 – Enemy AI Fails To Detect Player After Stealth Reset

> **Portfolio Note:** Fictional QA portfolio example. Created for demonstration of bug-reporting technique and not presented as a confirmed defect in the live game.

## Game
Cyberpunk 2077

## Platform
PC

## Category
Gameplay / AI / Stealth

## Severity
Major

## Priority
High

## Frequency
4/5

## Description
An enemy can remain in an unaware state after the player has moved into a clearly visible position following a completed stealth reset.

## Preconditions
- Player is inside an enemy-controlled area.
- At least one hostile NPC is present.
- Stealth state can be reset by breaking line of sight.

## Steps to Reproduce
1. Enter a hostile area while undetected.
2. Trigger enemy awareness without being detected for a full combat state.
3. Break line of sight and move to a new visible position.
4. Wait for the enemy alert state to return to neutral.
5. Re-enter the enemy's field of view without attacking.

## Expected Result
The enemy detects the player and transitions to an appropriate alert or combat state.

## Actual Result
The enemy remains unaware despite having a clear line of sight.

## Impact
Stealth encounters can become inconsistent and allow the player to bypass intended enemy detection behavior.

## Suggested Verification
Repeat with different enemy archetypes, lighting conditions, distances, and difficulty settings.