---
title: 'Retrieve Connected Realm'
routable: false
verb: get
path: '/data/wow-connected-realm/{connectedrealmid}'
parameters:
    items:
        -
            name: connectedrealmid
            description: 'The id of the connected realm.'
query:
    items:
        -
            name: namespace
            description: 'The `namespace` that should be used to locate this document.'
            type:
                string: true
                array: false
                boolen: false
                float-negative: false
                float-positive: false
                hash: false
                integer-negative: false
                integer-positive: false
                list: false
                'null': false
                object: false
                timestamp: false
                zero: false
            example: dynamic-us
            allowed-values:
                - dynamic-eu
                - dynamic-kr
                - dynamic-tw
                - dynamic-us
        -
            name: locale
            description: 'The `locale` that should be reflected in localized data. All locales are returned by default, however you can use a locale key to return a specific locale.'
            type:
                string: true
                array: false
                boolen: false
                float-negative: false
                float-positive: false
                hash: false
                integer-negative: false
                integer-positive: false
                list: false
                'null': false
                object: false
                timestamp: false
                zero: false
            example: en_US
            allowed-values:
                - de_DE
                - en_US
                - es_ES
                - es_MX
                - fr_FR
                - it_IT
                - ko_KR
                - pt_BR
                - pt_PT
                - ru_RU
                - zh_CN
                - zh_TW
---

