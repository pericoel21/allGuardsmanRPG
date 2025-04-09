---
tags:
  - tag
aliases:
  - List of Tags
  - Tag List
  - Tags
  - Feats
abstract: list of all tags
status:
  - wip
---

```dataview
TABLE abstract as Abstract
FROM "os40k/tag-list"
SORT file.name ASC
WHERE file.name != "tag-list"
```