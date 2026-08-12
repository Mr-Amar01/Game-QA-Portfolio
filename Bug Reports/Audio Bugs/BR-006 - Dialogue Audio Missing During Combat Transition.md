# BR-006 – Dialogue Audio Missing During Combat Transition

> **Portfolio Note:** Fictional QA portfolio example created for portfolio demonstration.

## Game
Cyberpunk 2077

## Platform
PC

## Category
Audio / Dialogue

## Severity
Major

## Priority
Medium

## Frequency
3/5

## Description
A character dialogue line can fail to play when a scripted conversation begins immediately after a combat state transition.

## Preconditions
- A scripted encounter containing dialogue is available.
- Player can trigger the encounter while enemies are nearby.

## Steps to Reproduce
1. Approach the encounter.
2. Trigger the combat state.
3. Quickly complete or exit the combat sequence.
4. Trigger the scripted dialogue immediately afterward.
5. Observe dialogue playback.

## Expected Result
All intended dialogue lines play with synchronized subtitles and character animation.

## Actual Result
A dialogue line is skipped or silent while the associated subtitle or animation may still occur.

## Impact
Story context and character dialogue can be missed by the player.

## Suggested Verification
Test with subtitles enabled/disabled, different audio languages, headphones/speakers, and repeated save reloads.