# BR-006 – Network Reconnection Returns Player With Incorrect HUD State

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
Networking / UI

## Severity
High

## Priority
High

## Description
After a temporary network interruption and successful reconnection, the player can return to the match with one or more HUD elements displaying an outdated state.

## Preconditions
- Active match.
- Temporary network interruption can be simulated in a controlled test environment.

## Steps to Reproduce
1. Join an active match.
2. Record the current HUD state.
3. Simulate a temporary network interruption.
4. Restore network connectivity.
5. Allow the client to reconnect.
6. Compare the HUD with the current match state.

## Expected Result
All HUD elements synchronize with the authoritative match state after reconnection.

## Actual Result
A HUD element may temporarily display stale information after reconnection.

## Impact
Can mislead the player and indicate an incorrect gameplay state.

## Reproduction Rate
3/5