---
title: 'Retrieve recipe'
verb: get
path: '/wow/recipe/{recipeid}'
parameters:
    items:
        -
            name: recipeid
            description: 'The Id of the recipe.'
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

