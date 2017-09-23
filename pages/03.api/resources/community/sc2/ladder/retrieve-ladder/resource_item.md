---
title: 'Retrieve ladder'
routable: false
verb: get
path: '/sc2/ladder/{id}'
parameters:
    items:
        -
            name: id
            description: 'The `id` of the ladder to retrieve'
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

