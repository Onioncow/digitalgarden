---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-bestiary/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("Creatures")
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true
    order:
      - file.name
      - CreatureType

```

