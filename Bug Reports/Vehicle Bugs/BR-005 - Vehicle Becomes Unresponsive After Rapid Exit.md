# BR-005 – Vehicle Becomes Unresponsive After Rapid Exit

> **Portfolio Note:** Fictional QA portfolio example created for demonstration of gameplay defect reporting.

## Game
Cyberpunk 2077

## Platform
PC

## Category
Vehicles / Input

## Severity
Major

## Priority
High

## Frequency
2/5

## Description
After rapidly exiting and immediately attempting to re-enter a vehicle during a transition, the vehicle interaction prompt can fail to appear.

## Preconditions
- Player is driving a controllable vehicle.
- Player is near a valid vehicle exit location.

## Steps to Reproduce
1. Enter a vehicle.
2. Stop close to another interactable object or NPC.
3. Exit the vehicle.
4. Immediately attempt to re-enter the same vehicle.
5. Repeat the input during the transition window if necessary.

## Expected Result
The vehicle interaction prompt appears and the player can re-enter normally.

## Actual Result
The vehicle does not respond to the interaction input for a short period and the expected prompt may be absent.

## Impact
Vehicle traversal can be interrupted and may require the player to move away and return.

## Suggested Verification
Test different vehicle types, controller and keyboard input, crowded locations, and repeated enter/exit cycles.