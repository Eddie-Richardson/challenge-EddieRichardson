# Challenge Portfolio – Eddie Richardson

![Sync from Club Repo](https://github.com/Eddie-Richardson/challenge-EddieRichardson/actions/workflows/sync.yml/badge.svg)

This repository automatically syncs from the club repo every Sunday at 4 AM EST.

## Branch Structure

- **workflow** (default branch): contains only the GitHub Action that keeps this repo in sync.  
- **challengeX-tierY** branches: contain the actual challenge code.  
  - Example: `challenge4-tier1`, `challenge4-tier2`, `challenge4-tier3`  
  - Future challenges will follow the same pattern: `challenge5-tier1`, `challenge5-tier2`, etc.

Each tier branch represents a progressively more advanced version of the same challenge.

## How to Browse

- Start with the lowest tier branch (e.g. `challenge4-tier1`) to see the baseline solution.  
- Move up through `tier2` and `tier3` to see progressively more advanced implementations.  
- Each challenge is isolated by branch naming, so you can check out any `challengeX-tierY` branch directly.
