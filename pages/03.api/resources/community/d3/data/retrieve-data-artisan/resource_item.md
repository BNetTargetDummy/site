---
title: 'Retrieve data artisan'
routable: false
verb: get
path: '/d3/data/artisan/{artisan}'
parameters:
    items:
        -
            name: artisan
            description: 'The `artisan` data to retrieve.'
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

