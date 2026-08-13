---
{"dg-publish":true,"permalink":"/05-world/material-plane/01-geography/land/vitria/","dg-note-properties":{"cssclasses":["wide-page"]}}
---

>[!blank|float-right-medium]
>![Pasted image 20250425143552.png](/img/user/z_Assets/Pasted%20image%2020250425143552.png)
>
>>[!info]+ General Info
>>This is an example description of the entire continent including any relevant history or specific religious connotations 


```base
views:
  - type: table
    name: Vitria
    filters:
      and:
        - file.hasTag("Creatures")
        - not:
            - file.inFolder("z_Templates")
        - CommonLocations.contains(link("Vitria"))
    order:
      - file.name
      - CreatureType
      - file.tags
      - CommonLocations
    sort:
      - property: CreatureType
        direction: ASC
      - property: file.name
        direction: ASC
    columnSize:
      note.CommonLocations: 321
    rowHeight: medium

```

# Northern Vitria
>[!tip]+ Desc and Fauna
>This is an example description of the specific area




# River Magnum
>[!tip]+ Desc and Fauna
>This is an example description of the specific area




# Blackrock Forest Novum
>[!tip]+ Desc and Fauna
>This is an example description of the specific area



# Mediwood
>[!tip]+ Desc and Fauna
>This is an example description of the specific area



# Leaping Bog
>[!tip]+ Desc and Fauna
>This is an example description of the specific area



# Inferus Forest
>[!tip]+ Desc and Fauna
>This is an example description of the specific area



# Agros Fields
>[!tip]+ Desc and Fauna
>This is an example description of the specific area



# The Hollow Slopes of Vitria
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

