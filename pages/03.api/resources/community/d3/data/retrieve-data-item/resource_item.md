---
title: 'Retrieve data item'
verb: get
path: '/d3/data/item/{data}'
parameters:
    items:
        -
            name: data
            description: 'The ''data'' to profile'
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

