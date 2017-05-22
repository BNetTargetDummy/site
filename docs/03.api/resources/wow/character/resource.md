---
title: Character
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: true
order_by: ''
order_manual: ''
---

The Character Profile API is the primary way to access character information. This Character Profile API can be used to fetch a single character at a time through an HTTP GET request to a URL describing the character profile resource. By default, a basic dataset will be returned and with each request and zero or more additional fields can be retrieved. To access this API, craft a resource URL pointing to the character who's information is to be retrieved.