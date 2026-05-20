---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-bestiary/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("02 Lore/Bestiary")
        - note["dg-publish"] == true
    groupBy:
      property: CreatureType
      direction: ASC
    order:
      - file.name
      - CreatureType

```

