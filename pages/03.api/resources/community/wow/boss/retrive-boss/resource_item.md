---
title: 'Retrieve boss'
verb: get
path: '/wow/boss/{bossid}'
parameters:
    items:
        -
            name: bossid
            description: 'The `id` of the boss'
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

