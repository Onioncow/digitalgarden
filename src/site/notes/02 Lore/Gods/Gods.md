---
{"dg-publish":true,"permalink":"/02-lore/gods/gods/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("God")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - GodLevel
      - Domain
    sort:
      - property: GodLevel
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      note.GodLevel: 131

```
