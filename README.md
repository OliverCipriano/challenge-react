# Disney Character Search – Technical Challenge

This project is based on a React technical challenge.

## Bug Fix

The original implementation had a search issue caused by React's asynchronous state updates.
The API request was using a stale state value, causing the search results to lag one character behind.

### Fix applied

I corrected the issue by using the current input value directly when making the API request instead of relying on the outdated state variable.

## Tech Stack

- React
- TypeScript
- Disney API
