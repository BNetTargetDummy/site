---
title: 'Retrieve data rewards'
routable: false
verb: get
path: /sc2/data/rewards
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

