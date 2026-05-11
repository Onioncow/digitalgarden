---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-np-cs/","dg-note-properties":{}}
---


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
      - Race
      - currentLocation

```

