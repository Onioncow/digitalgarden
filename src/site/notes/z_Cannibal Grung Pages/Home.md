---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/home/","tags":["gardenEntry"],"dg-note-properties":{}}
---



# Player Characters
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
      - Campaign
      - file.name
      - Player
      - Age
      - Gender
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
      - Nation
      - file.name
      - Type
    sort:
      - property: Nation
        direction: ASC

```

