---
title: 'Retreive Realm'
routable: false
verb: get
path: '/data/wow/realm/{realmslug}'
parameters:
    items:
        -
            name: realmslug
            description: 'The `slug` of the realm. NOTE: An integer `id` of the realm has been tested to work as well.'
query:
    items:
        -
            name: namespace
            description: 'The `namespace` that should be used to locate this document. Valid namespaces are as follows: `dynamic-us`, `dynamic-eu`, `dynamic-kr`, and `dynamic-tw`.'
            type: string
            required: '1'
        -
            name: locale
            description: 'The `locale` that should be reflected in localized data. All locales are returned by default, however you can use a locale key to return a specific locale. Valid locales are as follows: `en_US`, `es_MX`, `pt_BR`, `de_DE`, `es_ES`, `fr_FR`, `it_IT`, `pt_PT`, `ru_RU`, `ko_KR`, `zh_TW`, and `zh_CN`.'
            type: string
            required: '0'
---

