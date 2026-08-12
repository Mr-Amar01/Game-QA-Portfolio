# TC-PUBG-006 – Verify Matchmaking State After App Resume

## Module
Matchmaking / Lifecycle

## Priority
Medium

## Type
Functional / Recovery

## Objective
Verify that matchmaking state remains accurate when the application is backgrounded and resumed.

## Preconditions
- Matchmaking has started.

## Steps
1. Start matchmaking.
2. Background the application.
3. Wait for a controlled period.
4. Resume the application.
5. Observe matchmaking status.

## Expected Result
The UI immediately reflects the current matchmaking state.

## Pass Criteria
No stale queue status or duplicate matchmaking action is displayed.