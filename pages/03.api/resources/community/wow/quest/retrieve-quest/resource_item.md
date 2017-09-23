---
title: 'Retrieve quest'
routable: false
verb: get
path: '/wow/quest/{questid}'
parameters:
    items:
        -
            name: questid
            description: 'The ID of the quest.'
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

