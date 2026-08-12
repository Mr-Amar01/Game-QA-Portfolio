# BR-006 – Background Resume Displays Stale Matchmaking Status

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Lifecycle / UI

## Severity
Medium

## Priority
Medium

## Description
After the application is backgrounded during matchmaking and then resumed, the matchmaking UI can display a stale status instead of the current queue state.

## Preconditions
- Matchmaking has started.
- Application can be sent to background.

## Steps to Reproduce
1. Start matchmaking.
2. Send the application to the background.
3. Wait while matchmaking continues.
4. Resume the application.
5. Observe the matchmaking status.

## Expected Result
The UI reflects the current matchmaking state immediately after resume.

## Actual Result
The displayed status may remain stale until the matchmaking screen refreshes.

## Impact
Can confuse the player about whether matchmaking is active.

## Reproduction Rate
3/5