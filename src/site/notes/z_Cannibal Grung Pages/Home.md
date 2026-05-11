---
{"dg-publish":true,"permalink":"/z-cannibal-grung-pages/home/","tags":["gardenEntry"],"dg-note-properties":{}}
---

>[!info]- Quick Links
>- [[04 Player Characters/04 Player Characters\|04 Player Characters]]
>- [[02 Lore/Artefacts/Artefacts\|Artefacts]]
>- [[02 Lore/Bestiary/Bestiary\|02 Lore/Bestiary/Bestiary]]
>- [[02 Lore/Gods/Gods\|Gods]]
>- [[03 NPCs Assorted/03 NPCs Assorted\|NPC's]]
>- [[z_Cannibal Grung Pages/Material Plane Maps\|Material Plane Maps]]




# Player Characters
```base
views:
  - type: table
    name: Player Characters
    filters:
      and:
        - file.hasTag("PC")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - Player
      - Age
      - Gender
  - type: table
    name: Settlements
    filters:
      and:
        - file.hasTag("Settlement")
        - not:
            - file.inFolder("z_Templates")
    order:
      - file.name
      - dg-publish
      - Nation
      - Type

```

