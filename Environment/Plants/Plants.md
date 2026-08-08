---
tags:
  - material_overview
aliases:
  - Plant
---
# Overview
This documents contain a variety of different plants, which is a type of [[Materials Overview|Material]].
# List of Plants
```dataview
TABLE WITHOUT ID
file.link AS "Plant",
family AS "Family",
properties AS "Properties",
rarity AS "Rarity",
cost_plant AS Cost
FROM #material AND #plant
SORT file.link AND family ASC
```