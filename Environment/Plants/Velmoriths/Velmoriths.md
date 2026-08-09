---
tags:
  - material
  - plant-family
aliases:
  - Chtoflora
  - Gizbitki
meta-links:
  - "[[Plants]]"
---
Velmoriths are a family of [[Plants|Plants]] that retract down into the ground when they sense any movement. These plants are often small, such as blades of grass or small flowers.

Different cultures have different names for these types of plants. The scientific community calls them [[Velmoriths|Chtoflora]], while people originating from [[Storms Reach Overview|Storms Reach]] call them [[Velmoriths|Gizbitki]], roughly translating to "Hidden Plant".
```dataview
TABLE WITHOUT ID
file.link AS "Plant",
family AS "Family",
properties AS "Properties",
rarity AS "Rarity",
cost_plant AS Cost
FROM #material AND #plant
SORT file.link AND family ASC
WHERE family = [[Velmoriths]]
```