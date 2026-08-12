# TC-FH5-006 – Verify Online Race Synchronization

## Module
Online Multiplayer / Networking

## Type
Network Recovery / Functional

## Priority
High

## Objective
Verify that remote vehicle positions remain synchronized during an online race under normal and controlled network conditions.

## Preconditions
- Online multiplayer session.
- At least two players in the race.

## Steps
1. Join an online race.
2. Observe nearby vehicles during straight sections and corners.
3. Introduce controlled network latency.
4. Continue observing remote vehicle movement.
5. Compare displayed race positions with the current race state.

## Expected Result
Remote vehicles remain within acceptable synchronization and recover smoothly from temporary network variation.

## Pass Criteria
No persistent desynchronization or incorrect race-state display occurs.