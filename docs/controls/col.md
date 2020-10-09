---
title: Col
sidebar_label: Col
slug: col
---

Represents a **column** to layout content. Column must be nested inside [rows](/docs/controls/row).

## Properties

### `id`

Control ID. Auto-generated if not specified explicitly.

### `width`

Column width is the number between `1` and `12`.

### `visible`

`true` - the control is visible; `false` - control is hidden, but still takes up space in the layout.

## Examples

Bash example to add two columns to a row with `header` ID:

```bash
'add col id=left to=header' > $PAGE_PIPE
'add col id=right to=header' > $PAGE_PIPE
```