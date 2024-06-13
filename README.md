---
title: README
description: 
published: true
date: 2024-06-13T09:37:10.365Z
tags: 
editor: markdown
dateCreated: 2024-06-13T09:37:08.466Z
---

# techwatch

This section contains some experiments in importing content into GitBook. For example taking DOCX source files and generating HTML versions using [pandoc](https://pandoc.org/).

```
pandoc source.docx -o target.md --wrap=none -t commonmark_x --extract-media=.
```

