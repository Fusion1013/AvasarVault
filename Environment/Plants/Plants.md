---
tags:
  - material_overview
aliases:
  - Plant
meta-links:
  - "[[Materials Overview]]"
---
# Overview
This documents contain a variety of different plants.
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
WHERE file.link != "Plant"
```