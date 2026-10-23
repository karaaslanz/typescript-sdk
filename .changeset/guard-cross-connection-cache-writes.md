---
'@modelcontextprotocol/client': patch
---

Reject cache writes captured on a previous connection, so stale responses cannot overwrite current entries or be placed into another server identity's partition after reconnect.
