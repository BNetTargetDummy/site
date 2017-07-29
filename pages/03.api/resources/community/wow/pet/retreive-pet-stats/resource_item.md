---
title: 'Retreive pet stats'
verb: get
path: '/wow/pet/stats/{speciesid}'
parameters:
    items:
        -
            name: speciesid
            description: 'The ID of the pet species.'
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

