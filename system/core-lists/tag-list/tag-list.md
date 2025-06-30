---
tags:
  - tag
aliases:
  - List of Tags
  - Tag List
abstract: list of all tags
status:
  - wip
---

```dataview
TABLE abstract as Abstract
FROM "system/tag-list"
SORT file.name ASC
WHERE file.name != "tag-list"
```