---
title: 'Retrieve era'
routable: false
verb: get
path: '/data/d3/era/{id}'
parameters:
    items:
        -
            name: id
            description: 'The era to lookup'
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: '1'
    url_taxonomy_filters: '1'
---

