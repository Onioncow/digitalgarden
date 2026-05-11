---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-player-characters/","dg-note-properties":{}}
---


```base
views:
  - type: list
    name: Table
    filters:
      and:
        - file.hasTag("PC")
        - '!file.inFolder("z_Templates")'
        - note["dg-publish"] == true

```

