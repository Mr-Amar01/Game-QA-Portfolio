# Exploratory Testing Checklist

> Simulated portfolio document demonstrating exploratory test thinking.

## Gameplay State Exploration
- What happens when an action is performed during a transition?
- What happens when the player interrupts an animation?
- What happens when the player moves outside the intended path?
- What happens when multiple interactions are triggered quickly?

## UI Exploration
- Open menus during gameplay transitions.
- Navigate rapidly between screens.
- Confirm controls remain usable at screen boundaries.
- Test repeated button presses.
- Test cancel/back actions from every relevant state.

## Save / Load Exploration
- Save during an objective transition.
- Save immediately before and after an interaction.
- Reload after death or interruption.
- Verify world, inventory and quest state remain consistent.

## Online Exploration
- Disconnect and reconnect.
- Change network conditions.
- Join/leave during state transitions.
- Observe behavior when matchmaking or loading is interrupted.

## Mobile Exploration
- Background and resume.
- Rotate where supported.
- Receive notifications/calls.
- Switch networks.
- Observe behavior under low battery and thermal stress in controlled testing.

## Reporting
Record exact state, steps, frequency, environment and evidence for every reproducible issue.