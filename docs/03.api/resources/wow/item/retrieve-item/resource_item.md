---
title: 'Retrieve item'
verb: get
path: '/wow/item/{itemid}'
parameters:
    items:
        -
            name: itemid
            description: 'The ID of the item.'
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

