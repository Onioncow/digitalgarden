---
{"dg-publish":true,"permalink":"/02-lore/artefacts/artefacts/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("Magical_Artifacts")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - currentLocation
    columnSize:
      file.name: 268

```

