---
tags:
  - person/<%
  - tp.system.suggester(["major",
  - '"minor"],'
  - '["major",'
  - '"minor"])'
  - "%>"
  - <%
  - tp.system.prompt("What
  - region
  - are
  - they
  - from?",
  - '"")'
  - "%>"
  - <%
  - tp.system.suggester(["alive",
  - '"dead"],'
  - '["alive",'
  - '"dead"])'
  - "%>"
aliases: 
race: 
age: 
description: This text will appear in the overview section of the document
---
# <% tp.file.title %>
## Overview
```dataviewjs
var p = dv.current();
dv.span(p.description)
```
## Appearance
