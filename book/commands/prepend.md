---
title: prepend
layout: command
version: 0.59.1
usage: |
  Prepend a row to the table.
---

# `{{ $frontmatter.title }}`

<div style='white-space: pre-wrap;'>{{ $frontmatter.usage }}</div>

## Signature

```> prepend (row)```

## Parameters

 -  `row`: the row to prepend

## Examples

Prepend one Int item
```shell
> [1,2,3,4] | prepend 0
```

Prepend two Int items
```shell
> [2,3,4] | prepend [0,1]
```

Prepend Ints and Strings
```shell
> [2,nu,4,shell] | prepend [0,1,rocks]
```
