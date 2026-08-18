# BR-006 – Weather Transition Causes Temporary Lighting Pop

> Portfolio example for QA demonstration.

## Game
Red Dead Redemption 2

## Platform
PC

## Category
Graphics / Lighting

## Severity
Low

## Priority
Low

## Reproduction Rate
3/5

## Description
During a rapid transition between weather conditions, scene lighting can briefly change abruptly before settling into the expected visual state.

## Preconditions
- Free-roam environment with dynamic weather enabled.
- Player is outdoors.

## Steps to Reproduce
1. Enter an outdoor area.
2. Move through an area where a weather transition occurs.
3. Observe environmental lighting during the transition.
4. Repeat across different times of day.

## Expected Result
Lighting transitions smoothly with the weather state.

## Actual Result
A brief lighting pop can occur before the final lighting state is applied.

## Impact
Minor visual immersion and presentation issue.