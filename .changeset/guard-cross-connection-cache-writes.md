---
'@modelcontextprotocol/client': patch
---

Reject response-cache writes captured on a previous connection, preventing stale results from overwriting current cached data or crossing server identity partitions after reconnect.
