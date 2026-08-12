# BR-001 – Touch Input Becomes Unresponsive After App Resume

> Portfolio example for QA demonstration. Not a claim of a production defect discovered by the author.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Mobile / Touch Input

## Severity
High

## Priority
High

## Description
After the game is sent to the background and resumed, touch input can become temporarily unresponsive on the gameplay screen.

## Preconditions
- Active match.
- Game is running in the foreground.

## Steps to Reproduce
1. Join an active match.
2. Move the player and confirm touch input works.
3. Send the game to the background.
4. Wait several seconds.
5. Resume the game.
6. Attempt to move, aim and interact using touch controls.

## Expected Result
Touch controls respond immediately after the game resumes.

## Actual Result
One or more touch controls may fail to respond until the screen is interacted with again or the game state refreshes.

## Impact
Can prevent the player from responding during an active match.

## Reproduction Rate
3/5