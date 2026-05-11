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
        - not:
            - file.inFolder("z_Templates")

```
