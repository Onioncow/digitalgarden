---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/dg-np-cs/","dg-note-properties":{}}
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
        - file.inFolder("03 NPCs Assorted")
        - note["dg-publish"] == true
    order:
      - file.name
      - currentLocation
      - Race
      - Age
      - Gender
      - Status

```
