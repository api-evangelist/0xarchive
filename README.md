# 0xArchive

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

0xArchive is a replayable market-data archive for two decentralised perpetuals venues, Hyperliquid and Lighter, delivered as one REST API, one WebSocket API that carries both live subscriptions and historical replay on a single connection, bulk Parquet export, and a hosted MCP server. Hyperliquid coverage is split into four route families - core perpetuals, Spot, HIP-3 builder perps and HIP-4 binary outcome markets - each with its own symbol format and its own set of available data types. Beyond order books, trades, candles, funding, open interest and liquidations, the archive reconstructs order-level depth that the venues do not serve directly: L4 for the Hyperliquid families and L3 for Lighter. Access is unusually flat - every plan including Free reaches every route family, schema and served depth, and plans gate capacity and Free's rolling 30-day history window rather than route access. An agent can buy its own 30-day Build or Pro access with an x402 USDC payment on Base and receive an API key on settlement, with no human signup step.

**Areas:** Market Data · Historical Data · Cryptocurrency · DeFi · Perpetuals · Derivatives · Order Book · Hyperliquid · Lighter · HIP-3 · HIP-4 · Prediction Markets

## 0xArchive on APIs.io

Everything profiled for 0xArchive is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/0xarchive/](https://apis.io/providers/0xarchive/)** — or go straight to one of the APIs or properties below.

### APIs (55)

- [0xArchive WebSocket API](https://apis.io/apis/0xarchive/0xarchive-websocket-api/) — Real-time subscriptions for supported Hyperliquid channels and historical replay for Hyperliquid and Lighter. Clients authenticate during the handshake with…
- [0xArchive Hosted MCP](https://apis.io/apis/0xarchive/0xarchive-hosted-mcp/) — Read-only market-data discovery and retrieval for MCP clients. Hosted MCP uses client-managed OAuth and requires no 0xArchive API key.
- [0xArchive Data Quality API](https://apis.io/apis/0xarchive/0xarchive-data-quality-api/) — Data quality monitoring: system status, coverage, incidents, latency, and SLA metrics.
- [0xArchive HIP-3 Builder Perps - Breadth API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-breadth-api/) — HIP-3 market breadth snapshots: percentage of eligible instruments trading above their current UTC-session VWAP.
- [0xArchive HIP-3 Builder Perps - Candles API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-candles-api/) — HIP-3 Builder Perps OHLCV candle data. Intervals: 1m, 5m, 15m, 30m, 1h, 4h, 1d, 1w. Coverage is symbol-specific; verify the selected market before choosing…
- [0xArchive HIP-3 Builder Perps - Convenience API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-convenience-api/) — HIP-3 convenience endpoints: freshness, summary, and price history.
- [0xArchive HIP-3 Builder Perps - Full-Depth L2 Order Book API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-full-depth-l2-order-book-api/) — Full-depth aggregated L2 order book snapshots, checkpoint history, and diffs for HIP-3 builder perps derived from L4 data. Full-depth checkpoints and diffs…
- [0xArchive HIP-3 Builder Perps - Funding API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-funding-api/) — HIP-3 Builder Perps funding rate history. Coverage is symbol-specific; inspect `/v1/symbols` `coverage_by_type.funding` before choosing a time range.
- [0xArchive HIP-3 Builder Perps - Instruments API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-instruments-api/) — HIP-3 Builder Perps instrument discovery. Use this route with `/v1/symbols` `coverage_by_type` to resolve the current inventory and schema-specific dates.
- [0xArchive HIP-3 Builder Perps - L4 Order Book API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-l4-order-book-api/) — Individual order-level (L4) orderbook data for HIP-3 builder perps.
- [0xArchive HIP-3 Builder Perps - Liquidations API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-liquidations-api/) — HIP-3 Builder Perps liquidation-related fills. Coverage is symbol-specific; verify the selected market before choosing a time range.
- [0xArchive HIP-3 Builder Perps - Open Interest API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-open-interest-api/) — HIP-3 Builder Perps historical open interest data. Coverage is symbol-specific; inspect `/v1/symbols` `coverage_by_type.oi` before choosing a time range.
- [0xArchive HIP-3 Builder Perps - Oracle API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-oracle-api/) — The HIP-3 Builder Perps - Oracle API from 0xArchive — 2 operation(s) for hip-3 builder perps - oracle.
- [0xArchive HIP-3 Builder Perps - Order Book API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-order-book-api/) — HIP-3 Builder Perps venue-native L2 order book snapshots. Native Hyperliquid source snapshots are capped at 20 levels per side; use the full-depth L2 routes…
- [0xArchive HIP-3 Builder Perps - Orders API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-orders-api/) — Order lifecycle events for HIP-3 builder perps.
- [0xArchive HIP-3 Builder Perps - Trades API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-trades-api/) — HIP-3 Builder Perps historical trade/fill data. Coverage is symbol-specific; inspect `/v1/symbols` `coverage_by_type.trades` before choosing a time range.
- [0xArchive HIP-3 Builder Perps - Wallets API](https://apis.io/apis/0xarchive/0xarchive-hip-3-builder-perps-wallets-api/) — The HIP-3 Builder Perps - Wallets API from 0xArchive — 1 operation(s) for hip-3 builder perps - wallets.
- [0xArchive HIP-3 - Liquidations API](https://apis.io/apis/0xarchive/0xarchive-hip-3-liquidations-api/) — The HIP-3 - Liquidations API from 0xArchive — 2 operation(s) for hip-3 - liquidations.
- [0xArchive HIP-3 - Orders API](https://apis.io/apis/0xarchive/0xarchive-hip-3-orders-api/) — The HIP-3 - Orders API from 0xArchive — 2 operation(s) for hip-3 - orders.
- [0xArchive HIP-4 Outcomes - Candles API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-candles-api/) — OHLCV candles for HIP-4 outcome sides. Prices are implied probabilities (0..1); quote_volume in USDH.
- [0xArchive HIP-4 Outcomes - Convenience API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-convenience-api/) — HIP-4 convenience endpoints: freshness, summary, and price history. `mark_price` for HIP-4 is an implied probability in [0,1], not a USD price.
- [0xArchive HIP-4 Outcomes - Instruments API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-instruments-api/) — HIP-4 per-side instrument discovery (one row per `#N` coin). Each outcome has two sides: side 0 (Yes) and side 1 (No). Coins are `#`-prefixed. Data from May…
- [0xArchive HIP-4 Outcomes - Open Interest API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-open-interest-api/) — HIP-4 outcome markets per-side open interest history. Display/paired/parity aggregates live on the `/outcomes/{outcome_id}` detail endpoint, not here. Data…
- [0xArchive HIP-4 Outcomes - Order Book API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-order-book-api/) — HIP-4 outcome markets L2 and L4 order book snapshots and diffs. Coins are referenced by numeric id (0, 1, 10, 11, ...); the `#`-prefixed form is also…
- [0xArchive HIP-4 Outcomes - Orders API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-orders-api/) — Order lifecycle events for HIP-4 outcome markets: placements, cancellations, fills, and TP/SL triggers.
- [0xArchive HIP-4 Outcomes - Outcomes API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-outcomes-api/) — HIP-4 outcome market discovery (one row per outcome, both sides combined). Use these to enumerate live and settled binary outcome markets. Data from May 2026.
- [0xArchive HIP-4 Outcomes - Questions API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-questions-api/) — The HIP-4 Outcomes - Questions API from 0xArchive — 2 operation(s) for hip-4 outcomes - questions.
- [0xArchive HIP-4 Outcomes - Trades API](https://apis.io/apis/0xarchive/0xarchive-hip-4-outcomes-trades-api/) — HIP-4 outcome markets historical trade/fill data. Data from May 2026.
- [0xArchive Hyperliquid - Candles API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-candles-api/) — Hyperliquid OHLCV candle data. Intervals: 1m, 5m, 15m, 30m, 1h, 4h, 1d, 1w.
- [0xArchive Hyperliquid - Convenience API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-convenience-api/) — Hyperliquid convenience endpoints: freshness, summary, and price history.
- [0xArchive Hyperliquid - Full-Depth L2 Order Book API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-full-depth-l2-order-book-api/) — Full-depth aggregated L2 order book snapshots, checkpoint history, and diffs for Hyperliquid perpetuals derived from L4 data. Full-depth checkpoints and…
- [0xArchive Hyperliquid - Funding API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-funding-api/) — Hyperliquid funding rate history. Data from May 2023.
- [0xArchive Hyperliquid - Instruments API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-instruments-api/) — Hyperliquid available trading instruments and their specifications. Authenticated inventory contains 232 core perpetual rows.
- [0xArchive Hyperliquid - L4 Order Book API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-l4-order-book-api/) — Individual resting-order (L4) book state for Hyperliquid perpetuals, including price, size, order ID, wallet attribution, queue priority, diffs, and…
- [0xArchive Hyperliquid - Liquidations API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-liquidations-api/) — Hyperliquid liquidation events with user attribution. The observed global floor is July 27, 2025; exact starts vary by symbol.
- [0xArchive Hyperliquid - Open Interest API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-open-interest-api/) — Hyperliquid historical open interest and market context data. Data from May 2023.
- [0xArchive Hyperliquid - Order Book API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-order-book-api/) — Hyperliquid venue-native L2 order book snapshots. Native Hyperliquid source snapshots are capped at 20 levels per side; use the full-depth L2 routes for…
- [0xArchive Hyperliquid - Orders API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-orders-api/) — Order lifecycle events for Hyperliquid perpetuals: placements, cancellations, fills, and TP/SL triggers.
- [0xArchive Hyperliquid Spot API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-spot-api/) — Hyperliquid Spot pair, order book, trade, reconstruction, TWAP, and freshness routes.
- [0xArchive Hyperliquid Spot - Candles API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-spot-candles-api/) — OHLCV candles for spot pairs (1m base, rolled up on demand).
- [0xArchive Hyperliquid Spot - Order Book API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-spot-order-book-api/) — The Hyperliquid Spot - Order Book API from 0xArchive — 1 operation(s) for hyperliquid spot - order book.
- [0xArchive Hyperliquid - Trades API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-trades-api/) — Hyperliquid historical trade/fill data with full execution details. Data from April 2023.
- [0xArchive Hyperliquid - Wallets API](https://apis.io/apis/0xarchive/0xarchive-hyperliquid-wallets-api/) — The Hyperliquid - Wallets API from 0xArchive — 1 operation(s) for hyperliquid - wallets.
- [0xArchive Legacy API](https://apis.io/apis/0xarchive/0xarchive-legacy-api/) — Deprecated endpoints that default to Hyperliquid. Use the exchange-specific endpoints (`/v1/hyperliquid/*`, `/v1/lighter/*`, `/v1/hyperliquid/hip3/*`) instead.
- [0xArchive Lighter - Candles API](https://apis.io/apis/0xarchive/0xarchive-lighter-candles-api/) — Lighter OHLCV candle data. Intervals: 1m, 5m, 15m, 30m, 1h, 4h, 1d, 1w. Data from August 2025.
- [0xArchive Lighter - Convenience API](https://apis.io/apis/0xarchive/0xarchive-lighter-convenience-api/) — Lighter convenience endpoints: freshness, summary, and price history.
- [0xArchive Lighter - Funding API](https://apis.io/apis/0xarchive/0xarchive-lighter-funding-api/) — Lighter funding rate history. Data from August 2025.
- [0xArchive Lighter - Instruments API](https://apis.io/apis/0xarchive/0xarchive-lighter-instruments-api/) — Lighter available trading instruments and their specifications.
- [0xArchive Lighter - L3 Order Book API](https://apis.io/apis/0xarchive/0xarchive-lighter-l3-order-book-api/) — Individual order-level (L3) orderbook data for Lighter. Data from March 2026.
- [0xArchive Lighter - Liquidations API](https://apis.io/apis/0xarchive/0xarchive-lighter-liquidations-api/) — The Lighter - Liquidations API from 0xArchive — 2 operation(s) for lighter - liquidations.
- [0xArchive Lighter - Open Interest API](https://apis.io/apis/0xarchive/0xarchive-lighter-open-interest-api/) — Lighter historical open interest data. Data from August 2025.
- [0xArchive Lighter - Order Book API](https://apis.io/apis/0xarchive/0xarchive-lighter-order-book-api/) — Lighter L2 order book snapshots with configurable granularity. Checkpoint history starts January 29, 2026; 30s/10s/1s start January 30, 2026; tick…
- [0xArchive Lighter - Trades API](https://apis.io/apis/0xarchive/0xarchive-lighter-trades-api/) — Lighter historical fill data across more than 200 markets. Served history begins August 27, 2025, with exact starts varying by market.
- [0xArchive System API](https://apis.io/apis/0xarchive/0xarchive-system-api/) — Health checks and system status
- [0xArchive Web3 Authentication API](https://apis.io/apis/0xarchive/0xarchive-web3-authentication-api/) — SIWE authentication for existing wallet accounts and autonomous paid wallet access via x402. Standard Free accounts are created through the browser signup flow.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [0Xarchive Websocket Channels](https://apis.io/asyncapis/0xarchive/0xarchive-websocket-channels/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [0xArchive MCP](https://apis.io/servers/0xarchive/0xarchive-mcp/)

#### Overlays (54)

OpenAPI overlays, including conversational phrasing for each operation.

- [0Xarchive Data Quality Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-data-quality-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Breadth Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-breadth-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Candles Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-candles-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Convenience Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-convenience-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Full Depth L2 Order Book Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-full-depth-l2-order-book-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Funding Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-funding-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Instruments Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-instruments-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps L4 Order Book Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-l4-order-book-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Liquidations Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-liquidations-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Open Interest Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-open-interest-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Oracle Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-oracle-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Order Book Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-order-book-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Orders Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-orders-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Trades Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-trades-api-phrasing-overlay/)
- [0Xarchive Hip 3 Builder Perps Wallets Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-builder-perps-wallets-api-phrasing-overlay/)
- [0Xarchive Hip 3 Liquidations Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-liquidations-api-phrasing-overlay/)
- [0Xarchive Hip 3 Orders Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-3-orders-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Candles Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-candles-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Convenience Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-convenience-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Instruments Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-instruments-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Open Interest Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-open-interest-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Order Book Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-order-book-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Orders Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-orders-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Outcomes Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-outcomes-api-phrasing-overlay/)
- [0Xarchive Hip 4 Outcomes Questions Api Phrasing Overlay](https://apis.io/overlays/0xarchive/0xarchive-hip-4-outcomes-questions-api-phrasing-overlay/)
- …and 29 more published on APIs.io

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [0Xarchive Authentication](https://apis.io/security/0xarchive/0xarchive-authentication/)
- [0Xarchive Domain Security](https://apis.io/security/0xarchive/0xarchive-domain-security/)
- [0Xarchive Vulnerability Disclosure](https://apis.io/security/0xarchive/0xarchive-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [0Xarchive Scopes](https://apis.io/scopes/0xarchive/0xarchive-scopes/)

#### Plans and pricing (2)

Published plans, tiers and prices.

- [0Xarchive Plans Pricing](https://apis.io/plans/0xarchive/0xarchive-plans-pricing/)
- [0Xarchive Price Estimates](https://apis.io/plans/0xarchive/0xarchive-price-estimates/)

#### Rate limits (1)

Published request limits.

- [0Xarchive Rate Limits](https://apis.io/rate-limits/0xarchive/0xarchive-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [0Xarchive Finops](https://apis.io/finops/0xarchive/0xarchive-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://0xarchive.io/)
- [Documentation](https://docs.0xarchive.io/)
- [Getting started](https://docs.0xarchive.io/quickstart)
- [API reference](https://docs.0xarchive.io/api-reference)
- [Pricing](https://0xarchive.io/pricing)
- [Sign up](https://0xarchive.io/signup)
- [Support](https://0xarchive.io/contact)
- [Changelog](https://0xarchive.io/changelog)
- [Blog](https://0xarchive.io/blog)
- [Security](https://0xarchive.io/.well-known/security.txt)
- [Terms of service](https://0xarchive.io/terms)
- [Privacy policy](https://0xarchive.io/privacy)
- [GitHub](https://github.com/0xArchiveIO)
- [Status](https://0xarchive.io/status)

## API Evangelist rating

**Kin Score 71.7** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 91.7 |
| Contract quality | 63.7 |
| Contract governance | 18.2 |
| Operational transparency | 71.1 |
| Developer ergonomics | 85.7 |
| Access clarity | 76.3 |

**Agent readiness 68.7** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 43.5** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/0xarchive/](https://apis.io/providers/0xarchive/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for 0xArchive: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/0xarchive/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
