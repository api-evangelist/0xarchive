---
name: 0xarchive-market-data
description: Choose 0xArchive venue families, endpoints, freshness checks, and response envelopes for route-safe market-data workflows.
---

# 0xArchive Market Data Skill

Use this skill when a user asks for market data, historical data, venue selection, or freshness checks.

## Inputs

- Venue family: Hyperliquid core, Hyperliquid Spot, HIP-3, HIP-4, or Lighter
- Symbol
- Data family
- Time range when historical data is requested
- API key environment variable

## Procedure

1. Pick the venue family from the docs.
2. Read OpenAPI for the exact route.
3. Add `X-API-Key`.
4. Use a bounded time range for history.
5. Include data-quality preflight for downstream workflows.
6. Preserve `meta.request_id`.

## Output

Return the route, example request, key response fields, pagination behavior, and any data-quality check the caller should run first.
