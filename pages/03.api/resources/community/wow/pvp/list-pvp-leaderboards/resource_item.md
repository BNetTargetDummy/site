---
title: 'List pvp leaderboards'
routable: false
verb: get
path: '/wow/leaderboard/{bracket}'
parameters:
    items:
        -
            name: bracket
            description: 'The bracket of the PvP leaderboard. Valid choices are `2v2`, 3v3`, 5v5`, `rbg`'
query:
    items:
        -
            name: locale
            description: 'The locale to use in the response'
            type: string
            required: '0'
        -
            name: jsonp
            description: 'Request data to be returned as a JsonP callback'
            type: boolen
            required: '0'
---

