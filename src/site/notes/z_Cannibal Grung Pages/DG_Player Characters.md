---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-player-characters/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("PC")
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true
    order:
      - file.name
      - Player
      - Status
      - Level
      - Race
      - Class
      - Age
      - Gender
    sort:
      - property: AC
        direction: DESC
    columnSize:
      note.Level: 89

```

