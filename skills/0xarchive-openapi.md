---
name: 0xarchive-openapi
description: Generate route-safe 0xArchive clients, typed examples, and API reference checks from the pinned live OpenAPI contract.
---

# 0xArchive OpenAPI Skill

Use this skill for code generation, route discovery, schema questions, and client integration.

## Source Order

1. `https://docs.0xarchive.io/openapi.json`
2. Endpoint Reference
3. Curated route-family pages
4. Quickstart and guide pages

## Rules

- Generate from OpenAPI route definitions, not memory.
- Keep auth as `X-API-Key`.
- Keep base URL as `https://api.0xarchive.io`.
- Use `meta.request_id` in logging examples.
- Use OpenAPI for Hyperliquid core, Hyperliquid Spot, HIP-3, HIP-4, Lighter, data quality, and wallet-auth route families.
- Do not add route families absent from OpenAPI.
