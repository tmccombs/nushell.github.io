---
title: du
layout: command
version: 0.59.1
usage: |
  Find disk usage sizes of specified items.
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> du (path) --all --deref --exclude --max-depth --min-size```

## Parameters

 -  `path`: starting directory
 -  `--all`: Output file sizes as well as directory sizes
 -  `--deref`: Dereference symlinks to their targets for size
 -  `--exclude {glob}`: Exclude these file names
 -  `--max-depth {int}`: Directory recursion limit
 -  `--min-size {int}`: Exclude files below this size

## Examples

Disk usage of the current directory
```shell
> du
```
