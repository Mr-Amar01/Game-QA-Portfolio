# TC-PUBG-001 – Verify Touch Controls After App Resume

## Module
Mobile Controls / Lifecycle

## Priority
High

## Type
Functional / Recovery

## Objective
Verify that touch controls remain responsive after the application is resumed from the background.

## Preconditions
- Active match.
- Touch controls configured.

## Steps
1. Start an active match.
2. Verify movement, aiming and interaction controls.
3. Background the application.
4. Wait several seconds.
5. Resume the application.
6. Test movement, aiming and interaction controls.

## Expected Result
All touch controls respond immediately and correctly after resume.

## Pass Criteria
No control requires an additional refresh or restart to become responsive.