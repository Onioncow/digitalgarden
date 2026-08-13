---
{"dg-publish":true,"permalink":"/05-world/material-plane/01-geography/land/tercus/","dg-note-properties":{"cssclasses":["wide-page"]}}
---

>[!blank|float-right-medium]
>![Pasted image 20250504180353.png](/img/user/z_Assets/Pasted%20image%2020250504180353.png)
>
>>[!info]+ General Info
>>This is an example description of the entire continent including any relevant history or specific religious connotations 


```base
views:
  - type: table
    name: Tercus
    filters:
      and:
        - file.hasTag("Creatures")
        - not:
            - file.inFolder("z_Templates")
        - CommonLocations.contains(link("Tercus"))
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


# Pluvia Jungle
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Harenae Desert
>[!tip]+ Desc and Fauna
>This is an example description of the specific area


# Southern Dunes
>[!tip]+ Desc and Fauna
>This is an example description of the specific area


# Kafto Grasslands
>[!tip]+ Desc and Fauna
>This is an example description of the specific area


# The Ashen Veil
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Sunderpeaks
>[!tip]+ Desc and Fauna
>This is an example description of the specific area
