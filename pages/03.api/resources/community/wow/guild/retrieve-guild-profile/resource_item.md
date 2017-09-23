---
title: 'Retrieve guild profile'
routable: false
verb: get
path: '/wow/guild/{realm}/{guildname}'
parameters:
    items:
        -
            name: realm
            description: 'The `realm` of the guild to retrieve.'
        -
            name: guildname
            description: 'The `guild name` to retrieve'
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
        -
            name: fields
            description: 'Specifies what data you want to retrieve. Fields can be includes as a `,` separated list. Valid choices are `achievements`, `challenge`,  `members`, `news`.'
            required: '0'
---

