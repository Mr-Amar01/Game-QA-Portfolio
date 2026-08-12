# Smoke Test Suite

> Simulated portfolio checklist used to demonstrate build-verification thinking.

## Purpose
Quickly determine whether a build is stable enough for deeper testing.

## Core Checks
- [ ] Game/application launches successfully
- [ ] Main menu loads without blocking error
- [ ] Player/profile can be selected or loaded
- [ ] New gameplay session can start
- [ ] Player movement and primary controls work
- [ ] Core combat/gameplay action works
- [ ] UI/HUD renders correctly
- [ ] Audio initializes correctly
- [ ] Save functionality works where applicable
- [ ] Load functionality works where applicable
- [ ] Matchmaking starts where applicable
- [ ] A representative gameplay loop can be completed
- [ ] Application can exit normally

## Decision
**PASS:** No critical smoke failure; deeper testing may proceed.

**FAIL:** A critical core-flow failure blocks broader testing until the build is triaged.