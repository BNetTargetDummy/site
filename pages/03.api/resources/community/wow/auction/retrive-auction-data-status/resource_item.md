---
title: 'Retrieve auction data status'
verb: get
path: '/wow/auction/data/{realm}'
parameters:
    items:
        -
            name: Realm
            description: 'The `realm`'
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
