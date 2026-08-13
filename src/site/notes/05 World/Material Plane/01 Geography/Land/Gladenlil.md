---
{"dg-publish":true,"permalink":"/05-world/material-plane/01-geography/land/gladenlil/","dg-note-properties":{"cssclasses":["wide-page"]}}
---

>[!blank|float-right-medium]
>![Pasted image 20250425143215.png](/img/user/z_Assets/Pasted%20image%2020250425143215.png)
>
>>[!info]+ General Info
>>This is an example description of the entire continent including any relevant history or specific religious connotations 


```base
views:
  - type: table
    name: Gladenil
    filters:
      and:
        - file.hasTag("Creatures")
        - not:
            - file.inFolder("z_Templates")
        - CommonLocations.contains(link("Gladenlil"))
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


# Mountains of Volantem Lacertae
>[!tip]+ Desc and Fauna
>This is an example description of the specific area


# Head of the Spear
>[!tip]+ Desc and Fauna
>This is an example description of the specific area


# Main Gladenlil
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

