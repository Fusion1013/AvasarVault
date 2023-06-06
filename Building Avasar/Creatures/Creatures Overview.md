---
tag: 
- overview
- creature
---
## List of Creatures
```dataview
TABLE
creature_type AS Type,
environment AS Environment
FROM #creature
WHERE creature_type != "TEMPLATE"
SORT creature_type ASC
```
