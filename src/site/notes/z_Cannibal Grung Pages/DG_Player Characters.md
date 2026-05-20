---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-player-characters/","dg-note-properties":{}}
---

```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("04 Player Characters")
        - note["dg-publish"] == true
    groupBy:
      property: Campaign
      direction: ASC
    order:
      - file.name
      - Player
      - Status
      - Level
      - Race
      - Class

```
