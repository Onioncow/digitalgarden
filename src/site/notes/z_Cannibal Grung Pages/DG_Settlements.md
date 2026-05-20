---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-settlements/","dg-note-properties":{}}
---


```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("Settlement")
        - note["dg-publish"] == true
    order:
      - file.name
      - Nation
      - Type

```

