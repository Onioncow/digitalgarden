---
{"dg-publish":true,"permalink":"/campaigns/hidden-ritual/hidden-ritual/","tags":["CampaignSummary"]}
---

### Players
![[Base_Player Characters.base#Hidden Ritual]]

### Sessions
```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.inFolder("Campaigns/Hidden Ritual")
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
