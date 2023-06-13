---
tags:
- person/<% tp.system.suggester(["major", "minor"], ["major", "minor"]) %>
- <% tp.system.prompt("What region are they from?", "") %>
- <% tp.system.suggester(["alive", "dead"], ["alive", "dead"]) %>
aliases:

# Content Generation
race:
age:
description:
---
# <% tp.file.title %>
## Overview
```dataviewjs
let group = dv.page("<% tp.file.path(true) %>")
dv.span(group.description)
```
## Appearance
