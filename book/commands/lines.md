---
title: lines
layout: command
version: 0.59.1
usage: |
  Converts input to lines
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> lines --skip-empty```

## Parameters

 -  `--skip-empty`: skip empty lines

## Examples

Split multi-line string into lines
```shell
> echo $'two(char nl)lines' | lines
```
