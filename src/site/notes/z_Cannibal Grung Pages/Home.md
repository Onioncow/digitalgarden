---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/home/","tags":["gardenEntry"],"dg-note-properties":{}}
---

>[!info]- Quick Links
>- [[04 Player Characters/04 Player Characters\|04 Player Characters]]
>- [[02 Lore/Artefacts/Artefacts\|Artefacts]]
>- [[02 Lore/Bestiary/Bestiary\|Bestiary]]
>- [[02 Lore/Gods/Gods\|Gods]]
>- [[03 NPCs Assorted/03 NPCs Assorted\|NPC's]]
>- [[z_Cannibal Grung Pages/Material Plane Maps\|Material Plane Maps]]

# Player Characters

```base
views:
  - type: cards
    name: All Players Cards
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
    groupBy:
      property: Campaign
      direction: ASC
    order:
      - file.name
      - Player
      - Status
      - Level
      - Race
      - Class
      - Campaign
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
    image: note.Pfp
    imageAspectRatio: 1
    cardSize: 370
  - type: table
    name: All Players
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
    groupBy:
      property: Campaign
      direction: ASC
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
      - Campaign
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
  - type: table
    name: Cousins DnD
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
        - Campaign == link("Cousins D&D")
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
      - property: Campaign
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      file.name: 276
      note.Player: 265
      note.SpecialFeatures: 294
      note.Class: 159
      note.Age: 120
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
  - type: table
    name: Monster Hunter
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
        - Campaign == link("Monster Hunter")
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
      - property: Campaign
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      file.name: 276
      note.Player: 265
      note.SpecialFeatures: 294
      note.Class: 159
      note.Age: 120
  - type: table
    name: One Shot Fellas
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
        - Campaign == link("One Shot Fellas")
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
        direction: DESC
      - property: Campaign
        direction: ASC
    columnSize: {}
    image: note.Pfp

```


(The databases are currently not supported so it looks a lil jank. Maybe one day it'll be updated but for now you will just have to use the navigation bar on the left.)
