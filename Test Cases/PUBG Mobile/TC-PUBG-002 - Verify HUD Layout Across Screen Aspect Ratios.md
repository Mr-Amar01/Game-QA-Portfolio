# TC-PUBG-002 – Verify HUD Layout Across Screen Aspect Ratios

## Module
UI / Device Compatibility

## Priority
High

## Type
Compatibility / Functional

## Objective
Verify that HUD controls remain correctly positioned and usable across supported device aspect ratios.

## Preconditions
- Supported Android devices with different aspect ratios.
- Custom HUD layout available.

## Steps
1. Configure a HUD layout near the screen edges.
2. Save the layout.
3. Launch a match.
4. Repeat on devices with different supported aspect ratios.
5. Check all interactive HUD elements.

## Expected Result
All controls remain within the safe area, are visible and do not overlap.

## Pass Criteria
HUD remains usable on every tested device configuration.