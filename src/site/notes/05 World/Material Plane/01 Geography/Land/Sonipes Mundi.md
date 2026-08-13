---
{"dg-publish":true,"permalink":"/05-world/material-plane/01-geography/land/sonipes-mundi/","dg-note-properties":{"cssclasses":["wide-page"]}}
---

>[!blank|float-right-medium]
>![Pasted image 20250504180320.png](/img/user/z_Assets/Pasted%20image%2020250504180320.png)
>
>>[!info]+ General Info
>>This is an example description of the entire continent including any relevant history or specific religious connotations 


```base
views:
  - type: table
    name: Sonipes Mundi
    filters:
      and:
        - file.hasTag("Creatures")
        - not:
            - file.inFolder("z_Templates")
        - CommonLocations.contains(link("Sonipes Mundi"))
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


# Western Sonipes
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Eastern Sonipes
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Nothern Tundra
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Horned Coast
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Mist Dragon Valley 
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Mountains of the Weeping Ghost
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Thunderhoof Peaks
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Howling Maw
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Pale Reach
>[!tip]+ Desc and Fauna
>This is an example description of the specific area
