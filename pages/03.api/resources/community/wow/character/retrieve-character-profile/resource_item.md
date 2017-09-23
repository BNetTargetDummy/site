---
title: 'Retrieve character profile'
routable: false
verb: get
path: '/wow/character/{realm}/{charactername}'
parameters:
    items:
        -
            name: realm
            description: 'The `realm` of the character to retrieve.'
        -
            name: charactername
            description: 'The `character name` to retrieve.'
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
            description: 'Specifies what data you want to retrieve. Fields can be includes as a `,` separated list. Valid choices are `achievements`, `appearance`, `feed`, `guild`, `hunterpets`, `items`, `mounts`, `pets`, `petslots`, `professions`, `progression`, `pvp`, `quests`, `reputation`, `statistics`, `stats`, `talents`, `titles`, `audit`.'
            required: '0'
---

