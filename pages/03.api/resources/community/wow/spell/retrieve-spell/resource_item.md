---
title: 'Retrieve spell'
routable: false
verb: get
path: '/wow/spell/{spellid}'
parameters:
    items:
        -
            name: spellid
            description: 'The id of the spell.'
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

