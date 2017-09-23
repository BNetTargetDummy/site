---
title: 'Retrieve item set'
routable: false
verb: get
path: '/wow/item/{setid}'
parameters:
    items:
        -
            name: setid
            description: 'The ID of the set'
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

