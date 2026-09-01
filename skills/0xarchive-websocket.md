---
name: 0xarchive-websocket
description: Build 0xArchive WebSocket subscriptions, replay flows, gap handling, and order-book reconstruction workflows.
---

# 0xArchive WebSocket Skill

Use this skill for live subscriptions, replay, gap handling, and reconstruction workflows.

## Procedure

1. Confirm WebSocket is the right interface. Use REST for one snapshot or current Lighter data.
2. Connect with `Authorization: Bearer $OXARCHIVE_API_KEY` in the opening handshake.
3. Subscribe to the exact supported live channel and symbol, or choose a Lighter replay channel.
4. Handle open, message, error, close, reconnect, and keep-alive.
5. For standard replay, include start, end, `speed`, and gap handling.
6. For Lighter channels, use `op: "replay"` with a bounded `start` and `end`; live subscriptions are not supported.
7. For Hyperliquid core L4 replay, request one core L4 channel, omit `speed`, and process `l4_snapshot` before `l4_batch`.
8. For reconstruction, include snapshot, ordered diffs, gap detection, and resync.

## Venue Notes

- Hyperliquid core channels use standard symbols such as `BTC`.
- Spot WebSocket channels are real-time-only. Use pair symbols such as `HYPE-USDC`.
- HIP-3 standard channels support standard replay and use prefixed symbols such as `km:US500`; HIP-3 L4 is live only.
- HIP-4 live WebSocket delivery covers trades and L4. Stored order-book and open-interest history supports standard replay; use REST for current order-book and open-interest reads.
- HIP-3 and HIP-4 L4 channels are real-time-only.
- Lighter channels support historical replay but not live subscriptions through the 0xArchive WebSocket. Use REST for current data and REST, WebSocket replay, or exports for historical data.
- Lighter standard and L3 channels support standard replay and are separate from Hyperliquid channels.
