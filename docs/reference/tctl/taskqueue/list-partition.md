---
id: list-partition
title: tctl taskqueue list-partition
sidebar_label: list-partition
description: How to list Task Queue partitions and the hostname for partitions using tctl.
tags:
  - reference
  - tctl
---

The `tctl taskqueue list-partition` command lists the partitions of a [Task Queue](/docs/content/what-is-a-task-queue) and the hostname for the partitions.

`tctl taskqueue list-partition --taskqueue <value>`

The following modifier controls the behavior of the command.

### `taskqueue`

_Required modifier_

How to specify a [Task Queue](/docs/content/what-is-a-task-queue).

Alias: `--tq`

**Example**

```
tctl taskqueue list-partition --taskqueue <value>
```
