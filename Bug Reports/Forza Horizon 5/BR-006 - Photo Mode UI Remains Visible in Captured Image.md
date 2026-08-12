# BR-006 – Photo Mode UI Remains Visible in Captured Image

> Portfolio example for QA demonstration.

## Game
Forza Horizon 5

## Platform
PC

## Category
Photo Mode / UI

## Severity
Low

## Priority
Low

## Frequency
2/5

## Description
A transient photo mode interface element can remain visible in a captured image when the capture is triggered during a UI transition.

## Preconditions
- Photo mode available.
- Capture function enabled.

## Steps to Reproduce
1. Enter Photo Mode.
2. Change a camera or photo setting.
3. Trigger image capture during the interface transition.
4. Review the captured image.

## Expected Result
The captured image contains only the intended scene and excludes photo mode controls.

## Actual Result
A transient UI element can appear in the captured image.

## Impact
Reduces quality of captured images.

## Reproduction Rate
2/5