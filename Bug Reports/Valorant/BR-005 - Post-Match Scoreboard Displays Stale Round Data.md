# BR-005 – Post-Match Scoreboard Displays Stale Round Data

> Portfolio example for QA demonstration.

## Game
VALORANT

## Platform
PC

## Category
UI / Match Results

## Severity
Medium

## Priority
Medium

## Description
The post-match scoreboard intermittently displays an outdated value for a round statistic immediately after the match concludes.

## Preconditions
- Match has completed.
- Player reaches the post-match results screen.

## Steps to Reproduce
1. Complete a match.
2. Open the post-match scoreboard.
3. Record the displayed round statistic.
4. Navigate away and return to the scoreboard.
5. Compare the values.

## Expected Result
The scoreboard consistently displays the final recorded match statistics.

## Actual Result
A statistic may initially display a stale value before updating after navigation.

## Impact
Reduces confidence in the accuracy of match-result information.

## Reproduction Rate
2/5