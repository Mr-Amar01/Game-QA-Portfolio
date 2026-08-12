# BR-004 – Incoming Call Interrupts Match Audio State

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Mobile Interruption / Audio

## Severity
Medium

## Priority
Medium

## Description
After an incoming call interrupts gameplay and the player returns to the match, game audio may not immediately return to the state that existed before the interruption.

## Preconditions
- Active match.
- Device capable of receiving calls.

## Steps to Reproduce
1. Join an active match.
2. Confirm game audio is working.
3. Receive or simulate an incoming call.
4. Return to the game after dismissing the call.
5. Observe game audio.

## Expected Result
Game audio resumes according to the previously selected settings.

## Actual Result
Audio may remain muted or at an incorrect state until the audio session is refreshed.

## Impact
Important gameplay audio cues may be unavailable after interruption.

## Reproduction Rate
3/5