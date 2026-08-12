# TC-PUBG-003 – Verify Wi-Fi to Mobile Data Recovery

## Module
Networking

## Priority
High

## Type
Recovery / Functional

## Objective
Verify that an active match recovers correctly when the device switches from Wi-Fi to mobile data.

## Preconditions
- Active match.
- Wi-Fi and mobile data available.

## Steps
1. Join a match using Wi-Fi.
2. Disable Wi-Fi while mobile data remains enabled.
3. Wait for network recovery.
4. Observe player, HUD and match state.

## Expected Result
The client reconnects and synchronizes with the current match state without requiring an application restart.

## Pass Criteria
No persistent stale state or unintended match termination occurs.