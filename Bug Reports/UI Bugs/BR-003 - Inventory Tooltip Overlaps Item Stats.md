# BR-003 – Inventory Tooltip Overlaps Item Stats

> **Portfolio Note:** Fictional QA portfolio example created to demonstrate UI defect documentation.

## Game
Cyberpunk 2077

## Platform
PC

## Category
UI / Inventory

## Severity
Major

## Priority
Medium

## Frequency
3/5

## Description
The item comparison tooltip overlaps the lower portion of the equipment statistics panel at a specific inventory window size, making some values difficult to read.

## Preconditions
- Player has multiple equippable items.
- Inventory is open.
- Game window is running at a non-native resolution or resized display configuration.

## Steps to Reproduce
1. Open the inventory.
2. Select an equipment item.
3. Move the cursor over an item that displays a comparison tooltip.
4. Use a supported windowed resolution where the inventory has limited horizontal space.
5. Observe the comparison panel.

## Expected Result
Tooltip elements remain within the UI boundaries and do not obscure important statistics.

## Actual Result
The comparison tooltip overlaps part of the statistics panel.

## Impact
Players may have difficulty comparing equipment and reading item attributes.

## Suggested Verification
Test common 16:9 and 16:10 resolutions, windowed/fullscreen modes, and different UI scale settings.