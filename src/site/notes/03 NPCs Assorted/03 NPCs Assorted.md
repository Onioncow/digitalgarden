---
{"dg-publish":true,"permalink":"/03-np-cs-assorted/03-np-cs-assorted/","dg-note-properties":{"cssclasses":["wide-page"]}}
---



```base
properties:
  note.currentLocation:
    displayName: Last Known Location
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasTag("npc")
        - file.inFolder("03 NPCs Assorted")
    order:
      - file.name
      - currentLocation
      - Race
      - Age
      - Gender
      - Titles
      - Status
      - dg-publish
    sort:
      - property: currentLocation
        direction: ASC
    columnSize:
      note.Titles: 357

```
