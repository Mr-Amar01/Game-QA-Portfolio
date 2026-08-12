# BR-007 – Download Progress Resets After Temporary Backgrounding

> Portfolio example for QA demonstration.

## Game
PUBG MOBILE / BGMI

## Platform
Android

## Category
Download / Lifecycle

## Severity
Medium

## Priority
Medium

## Description
When optional game resources are downloading, temporarily backgrounding the application can cause the displayed download progress to reset or become inconsistent with the actual downloaded data.

## Preconditions
- Optional resource download is available.
- Stable network connection.

## Steps to Reproduce
1. Start an optional resource download.
2. Confirm progress is increasing.
3. Background the application.
4. Wait briefly.
5. Resume the application.
6. Observe the download progress.

## Expected Result
Download progress is preserved and accurately reflects the amount already downloaded.

## Actual Result
The progress indicator may reset or display an incorrect value before synchronizing.

## Impact
Creates uncertainty about download status and may cause unnecessary repeated downloads.

## Reproduction Rate
3/5