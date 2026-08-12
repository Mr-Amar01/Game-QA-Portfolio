# BR-007 – Drivatar Position Desynchronizes During Online Race

> Portfolio example for QA demonstration.

## Game
Forza Horizon 5

## Platform
PC

## Category
Online Multiplayer / Networking

## Severity
High

## Priority
High

## Frequency
2/5

## Description
During an online race, another player's displayed vehicle position can temporarily differ from the state presented by the race system, resulting in visible position correction.

## Preconditions
- Online race with multiple players.
- Stable connection except for the controlled test condition.

## Steps to Reproduce
1. Join an online race.
2. Observe another player's vehicle near a checkpoint or corner.
3. Introduce a controlled network latency condition.
4. Continue observing the vehicle and race position.

## Expected Result
Remote vehicle movement remains synchronized within acceptable network interpolation limits.

## Actual Result
The remote vehicle can visibly correct its position after a synchronization delay.

## Impact
Can affect perceived race fairness and online driving quality.

## Reproduction Rate
2/5