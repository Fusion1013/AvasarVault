---
tags:
  - material_overview
aliases:
  - Metal
---
# Overview
This documents contain a variety of different metals, which is a type of [[Materials Overview|Material]].
# List of Metals
```dataview
TABLE WITHOUT ID
file.link AS "Material",
properties AS "Properties",
rarity AS "Rarity"
FROM #material AND #metal
SORT file.link ASC
```
# Planar Metals
Almost all planes have a Planar Metal associated with it. Three notable exceptions to this rule are the [[Material Plane]], [[Shadow Plane]] and [[Vibrant Plane]]. Instead, these three planes contain traces of all other Planar Metals.

Each Planar Metal is an aspect of the god that inhabits the plane. Some believe that the metal is a piece of the gods body, though there is evidence pointing towards the metal merely being a manifestation of the gods power on the plane. Nevertheless, these metals can be found in varying concentrations on the appropriate plane, as well as in small amounts on the material plane and its shadows.

Planar metals all inhabit special properties tied to its god.
```dataview
TABLE WITHOUT ID
file.link AS "Material",
plane AS "Plane",
properties AS "Properties",
rarity AS "Rarity"
FROM #material AND #metal AND #planar_metal
SORT file.link ASC
```