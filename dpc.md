---
title: DPC
description: Some web versions of DPC content
published: true
date: 2024-06-13T10:10:27.127Z
tags: 
editor: markdown
dateCreated: 2024-06-13T10:06:20.902Z
---

# DPC
This part of the wiki just contains some Markdown versions of items that are currently only published as PDF on the DPC website, https://dpconline.org

- Technology Watch
    - Guidance Notes
        - [wikidata-for-digital-preservationists](/dpc/techwatch/notes/wikidata-for-digital-preservationists)
        
        
The conversions were done by taking DOCX source files and generating HTML versions using [pandoc](https://pandoc.org/).

```
pandoc source.docx -o target.md --wrap=none -t commonmark_x --extract-media=.
```