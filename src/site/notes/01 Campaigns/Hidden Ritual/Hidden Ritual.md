---
{"dg-publish":true,"permalink":"/01-campaigns/hidden-ritual/hidden-ritual/","tags":["CampaignSummary"],"dg-note-properties":{"tags":["CampaignSummary"]}}
---

### Players

```base
views:
  - type: table
    name: Hidden Ritual
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
        - Campaign == link("Hidden Ritual")
    order:
      - file.name
      - Player
      - Status
      - Level
      - AC
      - PP
      - SpecialFeatures
      - Race
      - Class
      - Age
      - Gender
    sort:
      - property: file.name
        direction: ASC
      - property: Campaign
        direction: ASC
    columnSize:
      file.name: 276
      note.Player: 265
      note.SpecialFeatures: 294
      note.Class: 159
      note.Age: 120

```


### Sessions
```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("01 Campaigns/Hidden Ritual")
        - not:
            - file.hasTag("CampaignSummary")
    order:
      - file.name
      - day
      - levelUp
      - creationDate
    columnSize:
      file.name: 131
      note.levelUp: 354

```
