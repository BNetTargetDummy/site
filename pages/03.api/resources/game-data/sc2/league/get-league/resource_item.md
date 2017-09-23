---
title: 'Get league'
routable: false
verb: get
path: '/data/sc2/league/{season.id}/{queue.id}/{team.type}/{league.id}'
parameters:
    items:
        -
            name: season.id
            description: 'The `season id` to retrieve'
        -
            name: queue.id
            description: 'The `queue id` to retrieve'
        -
            name: team.type
            description: 'The `team type` to retrieve'
        -
            name: league.id
            description: 'The `league.id` to retrieve'
---

