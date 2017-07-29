---
title: 'Retrieve era leaderboard'
verb: get
path: '/data/d3/era/{id}/leaderboard/{leaderboard}'
parameters:
    items:
        -
            name: id
            description: 'The era to lookup'
        -
            name: leaderboard
            description: 'The leaderboard to lookup. You can find these strings in the [Era API call](#retrieve-era)'
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: '1'
    url_taxonomy_filters: '1'
---

