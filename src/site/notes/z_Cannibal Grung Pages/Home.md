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
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true
    order:
      - file.name
      - Player
      - Age
      - Level
      - Race
      - Class
      - Status
    sort:
      - property: file.name
        direction: ASC
    columnSize:
      note.Level: 80

```

# Settlements
```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("Settlement")
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true
    order:
      - file.name
      - Nation
      - Type

```

# NPC's  
```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("npc")
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true
    order:
      - file.name
      - currentLocation
      - Race
      - Age
      - Gender
      - Status

```

