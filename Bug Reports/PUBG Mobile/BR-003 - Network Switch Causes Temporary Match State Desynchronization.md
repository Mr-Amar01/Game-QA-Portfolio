# BR-003 – Network Switch Causes Temporary Match State Desynchronization

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Networking / Recovery

## Severity
High

## Priority
High

## Description
Switching from Wi-Fi to mobile data during an active match can temporarily leave the client displaying a stale gameplay state before synchronization completes.

## Preconditions
- Active match.
- Stable Wi-Fi connection.
- Mobile data available.

## Steps to Reproduce
1. Join an active match using Wi-Fi.
2. Record the current player and HUD state.
3. Disable Wi-Fi while keeping mobile data enabled.
4. Wait for the client to reconnect.
5. Observe the gameplay state.

## Expected Result
The client reconnects and synchronizes with the current authoritative match state.

## Actual Result
The client may temporarily display stale player or HUD information during recovery.

## Impact
Can cause misleading gameplay feedback and negatively affect competitive play.

## Reproduction Rate
3/5