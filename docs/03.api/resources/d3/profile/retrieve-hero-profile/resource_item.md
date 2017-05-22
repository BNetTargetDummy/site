---
title: 'Retrieve hero profile'
verb: get
path: '/d3/profile/{battletag}/hero/{id}'
parameters:
    items:
        -
            name: battletag
            description: 'The `battle tag` in the format `name-####` (ie. Noob-1234).'
        -
            name: id
            description: 'The `id` of the hero to retrieve.'
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

