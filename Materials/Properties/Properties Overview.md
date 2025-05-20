---
tags:
  - material_overview
aliases:
  - Property
---
# Overview
This documents contain a variety of properties, that are used by different [[Materials Overview|Materials]].
# List of Properties
%% DATAVIEW_PUBLISHER: start
```dataview
TABLE WITHOUT ID
file.link AS "Name",
description AS "Description"
FROM #material_property
WHERE description != null
SORT file.link ASC
```
%%
%% DATAVIEW_PUBLISHER: end