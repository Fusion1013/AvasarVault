---
aliases:
- Language
- Languages
- Language Group

todo: The language map looks kinda stupid, maybe redo it later
---
## Languages & Groups
```dataview
TABLE WITHOUT ID
file.link AS "Language/Group",
choice(language_group = null, "**Group**", "Language") AS "Type",
regions AS "Regions",
default(language_group, file.name) AS "Group"
FROM (#language AND -#Dead) OR #Language_Group
SORT (default(language_group, file.name)+choice(language_group = null, "Group", "Language")) ASC
```
![[Language Map.canvas|Language Map]]
