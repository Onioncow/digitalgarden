---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/settlements/","dg-note-properties":{}}
---



```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("Fort", "Settlement")
        - not:
            - file.inFolder("z_Templates")
    groupBy:
      property: Nation
      direction: ASC
    order:
      - file.name
      - Nation
      - Type
      - dg-publish
    sort:
      - property: Nation
        direction: ASC
      - property: Type
        direction: ASC
      - property: dg-publish
        direction: ASC
    columnSize:
      note.Type: 244

```
