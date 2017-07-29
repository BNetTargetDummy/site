---
title: 'Retrieve zone'
verb: get
path: '/wow/zone/{zoneid}'
parameters:
    items:
        -
            name: zoneid
            description: 'The ID of the zone.'
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

