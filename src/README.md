---
title: "Document Name"
tags: [project, tags]
---

# Document Name

It's an informational page of a document.

## Structure

```dataview
TABLE file.ctime as "Created"
FROM "chapters"
SORT file.name
```

## Commands

- Build PDF: `mise run build-pdf`
- Build Word: `mise run build-docx`
- Automatic build: `mise run watch`
