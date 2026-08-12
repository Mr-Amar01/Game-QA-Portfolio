# Regression Test Suite

> Simulated portfolio document.

## Purpose
Verify that previously working functionality remains stable after fixes, content changes or build updates.

## High-Risk Areas
### Quest / Progression
- [ ] Quest starts correctly
- [ ] Objective updates after completion
- [ ] Required interactions remain available
- [ ] Quest completion rewards are granted

### Gameplay
- [ ] Movement
- [ ] Primary attack/fire action
- [ ] Damage and health
- [ ] Death/restart flow

### UI
- [ ] Main HUD
- [ ] Menus
- [ ] Inventory
- [ ] Settings
- [ ] Notifications

### Save / Recovery
- [ ] Manual save
- [ ] Load previous save
- [ ] Checkpoint recovery
- [ ] State persists after restart

### Online / Network
- [ ] Matchmaking
- [ ] Match entry
- [ ] Disconnect recovery
- [ ] Match result synchronization

## Execution Rule
Prioritize areas affected by the latest fix, then execute the broader regression set based on risk.