# BR-005 – Performance Degradation After Extended Match Session

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Performance

## Severity
High

## Priority
High

## Description
After an extended gameplay session, frame-rate stability can degrade compared with the beginning of the session on the same device and graphics configuration.

## Preconditions
- Supported Android device.
- Consistent graphics and frame-rate settings.
- Device starts from a cool state.

## Steps to Reproduce
1. Launch the game.
2. Record initial performance under a controlled scenario.
3. Play multiple consecutive matches without restarting the application.
4. Repeat the same controlled scenario later in the session.
5. Compare frame-rate stability and input responsiveness.

## Expected Result
Performance remains within the expected range for the selected settings.

## Actual Result
Frame-rate stability may degrade after extended play.

## Impact
Can reduce aiming precision and overall gameplay responsiveness.

## Reproduction Rate
3/5