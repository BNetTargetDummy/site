---
title: 'List challenge realm leaderboard'
verb: get
path: '/wow/challenge/{realm}'
parameters:
    items:
        -
            name: realm
            description: 'The `realm` challege leaderboards to retrieve.'
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

