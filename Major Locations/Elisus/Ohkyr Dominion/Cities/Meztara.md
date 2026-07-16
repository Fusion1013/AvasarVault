---
tags:
  - city
nation: Ohkyr Dominion
population: 24000
meta-links:
  - "[[Ohkyr Dominion Overview|Ohkyr Dominion]]"
---
> [!infobox|right]
> # Meztara
> ![[placeholder.png]]
> ###### Geography
> | **Aliases** | ? |
> | - | - |
> | **Region** | ? |
> | **Size** | Metropolis |
> | **Terrain** | ? |
> ###### Society
> | **Demonym** | ? |
> | - | - |
> | **Races** | 48% Humans, 18% Dwarves, 12% Elves, 9% Gnomes |
> | **Religions** | ? |
> ###### Commerce
> | **Imports** | Raw Metal, Lumber, Spice, Fabric |
> | - | - |
> | **Exports** | Bronzeworks, Fittings |
> ###### Politics
> | **Type** | ? |
> | - | - |
> | **Allegiances** | ? |
> ###### History
> | **Population** | 24.000 in 1376 APC |
> | - | - |

*"QUOTE"*
# Overview
# History
# Culture
# Geography
## Landmarks
# Locations
# Organizations
```dataview
TABLE 
leaders AS "Leaders",
members AS "Members",
formed AS "Formed"
FROM #organization
WHERE base_of_operations = "CITY NAME"
SORT formed DESC
```
# People
```dataview
TABLE 
age AS "Age"
FROM #person
WHERE home = "CITY NAME"
```
