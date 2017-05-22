---
title: 'List profile match history'
verb: get
path: '/sc2/profile/{id}/{region}/{name}/matches'
parameters:
    items:
        -
            name: id
            description: 'The `id` of the profile'
        -
            name: region
            description: 'The `region` of the profile'
        -
            name: name
            description: 'The `name` of the profile'
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

