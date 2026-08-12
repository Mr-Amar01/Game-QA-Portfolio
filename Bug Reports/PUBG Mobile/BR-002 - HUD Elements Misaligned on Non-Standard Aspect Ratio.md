# BR-002 – HUD Elements Misaligned on Non-Standard Aspect Ratio

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
UI / Device Compatibility

## Severity
Medium

## Priority
Medium

## Description
A HUD control can become partially misaligned or overlap another UI element on a device with a non-standard screen aspect ratio.

## Preconditions
- Device with a supported but uncommon screen aspect ratio.
- Custom HUD layout enabled.

## Steps to Reproduce
1. Launch the game.
2. Open HUD customization.
3. Position a control near a screen edge.
4. Save the layout.
5. Start a match.
6. Observe the affected control.

## Expected Result
Controls remain within their intended safe area and do not overlap other interactive elements.

## Actual Result
A control may shift toward the screen edge or overlap another HUD element.

## Impact
Can reduce visibility or make an important control difficult to use.

## Reproduction Rate
3/5