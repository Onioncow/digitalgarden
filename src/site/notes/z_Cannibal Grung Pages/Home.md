---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/home/","tags":["gardenEntry"],"dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Player Characters
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - Player
      - Age
      - Gender
      - Campaign
    sort:
      - property: Campaign
        direction: ASC
      - property: file.name
        direction: ASC
  - type: table
    name: Settlements
    filters:
      and:
        - file.hasTag("Settlement")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - Type
      - Nation
    sort: []
  - type: table
    name: Bestiary
    filters:
      and:
        - file.hasTag("Creatures")
        - '!file.inFolder("z_Templates")'
    order:
      - file.name
      - CreatureType
    sort:
      - property: CreatureType
        direction: ASC

```

