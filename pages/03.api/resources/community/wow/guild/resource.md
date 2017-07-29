---
title: Guild
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: true
---

This guild profile API can be used to fetch a single guild at a time through an HTTP GET request to a url describing the guild profile resource. By default, a basic dataset will be returned and with each request and zero or more additional fields can be retrieved.