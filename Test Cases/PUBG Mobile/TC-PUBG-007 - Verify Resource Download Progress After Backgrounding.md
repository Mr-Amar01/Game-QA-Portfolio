# TC-PUBG-007 – Verify Resource Download Progress After Backgrounding

## Module
Resource Download / Lifecycle

## Priority
Medium

## Type
Functional / Recovery

## Objective
Verify that optional resource downloads preserve accurate progress when the application is temporarily backgrounded.

## Preconditions
- Optional resource download is available.
- Stable network connection.

## Steps
1. Start an optional resource download.
2. Record the displayed progress.
3. Background the application.
4. Wait briefly.
5. Resume the application.
6. Observe the progress indicator.

## Expected Result
Download progress is preserved and accurately reflects the downloaded data.

## Pass Criteria
No unexplained progress reset, duplicate download or incorrect completion state occurs.