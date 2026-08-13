---
{"dg-publish":true,"permalink":"/05-world/material-plane/01-geography/land/condeus/","dg-note-properties":{"cssclasses":["wide-page"]}}
---

>[!blank|float-right-medium]
>![Pasted image 20250426205554.png](/img/user/z_Assets/Pasted%20image%2020250426205554.png)
>
>>[!info]+ General Info
>>This is an example description of the entire continent including any relevant history or specific religious connotations 


```base
views:
  - type: table
    name: Condeus
    filters:
      and:
        - file.hasTag("Creatures")
        - not:
            - file.inFolder("z_Templates")
        - CommonLocations.contains(link("Condeus"))
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


# Eastern Condeus
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# By the Shattered Strait
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Perfumed Quag
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Misty Swamp
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Twin Jungles
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Riverwood
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Ashen Spires
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Wyrmcrest Range
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# The Shrouded Peaks
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Celestial Springs
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Inhaera Minor
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# South of the Inhaera River
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Forest Solitar
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Plains of Adula
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Tutella Jungle
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Tutella Plains
>[!tip]+ Desc and Fauna
>This is an example description of the specific area

# Searing Dunes
>[!tip]+ Desc and Fauna
>This is an example description of the specific area
