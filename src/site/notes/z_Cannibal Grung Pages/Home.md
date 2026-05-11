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
        - '!file.inFolder("z_Templates")'
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
