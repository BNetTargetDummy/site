---
title: 'Retrieve profile career'
routable: false
verb: get
path: '/d3/profile/{battletag}/'
parameters:
    items:
        -
            name: battletag
            description: 'The `battle tag ` of the player to retrieve. The format should be `name-####` (ie. Noob-1234)'
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

