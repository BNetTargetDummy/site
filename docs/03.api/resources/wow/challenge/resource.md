---
title: Challenge
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    pagination: true
---

The Challenge API resource endpoints contains data for the current set of challenge mode maps. The map field includes the current medal times for each dungeon. Inside each ladder is provided data about each character that was part of each recorded run. The character data includes the current cached spec of the character while the member field includes the spec of the character during the challenge mode run.