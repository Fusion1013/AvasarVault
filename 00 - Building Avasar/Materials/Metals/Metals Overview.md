---
tags:
- material_overview
---
## Overview
This documents contain a variety of different metals, which is a type of [[Materials Overview|Material]].
## List of Metals
```dataview
TABLE WITHOUT ID
file.link AS "Material",
description AS "Description",
properties AS "Properties",
rarity AS "Rarity",
cost_kg AS "Cost/kg",
cost_lb AS "Cost/lb"
FROM #material AND #metal
WHERE description != null
SORT file.link ASC
```
