---
title: 'Retrieve season leaderboard'
routable: false
verb: get
path: '/data/d3/season/{id}/leaderboard/{leaderboard}'
parameters:
    items:
        -
            name: id
            description: 'The season to lookup'
        -
            name: leaderboard
            description: 'The leaderboard to lookup. You can find these strings in the [Season API call](#retrieve-season)'
---

