# techwatch

This section contains some experiments in importing content into GitBook. For example taking DOCX source files and generating HTML versions using [pandoc](https://pandoc.org/).

```
pandoc source.docx -o target.md --wrap=none -t commonmark_x --extract-media=.
```

