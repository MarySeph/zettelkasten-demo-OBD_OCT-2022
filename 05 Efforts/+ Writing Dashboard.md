---
tags: space/work
---
up:: [[🏡 Home]]

# + Writing Dashboard

> Go to [[Blog Posts MOC]] to for all your efforts.


## In-progress

```dataview 
TABLE without id file.link as "Title", file.mtime as "Last Edited"
WHERE status="project/active" AND areas="writing" AND contains(tags, "project/nonfiction") 
SORT file.mtime ASC
```

##   Complete
```dataview 
TABLE without id file.link as "Title", file.mtime as "Last Edited"
WHERE status="project/complete" AND areas="writing" AND contains(tags, "project/nonfiction") 
SORT file.mtime ASC
```
