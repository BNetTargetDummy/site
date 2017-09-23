---
title: 'Retrieve pet ability'
routable: false
verb: get
path: '/wow/pet/ability/{abilityid}'
parameters:
    items:
        -
            name: abilityid
            description: 'The ID of the ability'
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

