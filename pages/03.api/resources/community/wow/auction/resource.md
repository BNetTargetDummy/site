---
title: Auction
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: true
---

The Auction endpoint currently provide snapshots of data about current auctions. Fetching auction dumps is a two step process. Step one involves checking a per-realm index file to determine if a recent dump has been generated and/or modified. To avoid fetching the large file, you can be checked the `last-modified` field returned as part of the request. The second step involves fetching the most recently generated dump file, a GZIP filed, with the JSON auction data schema.