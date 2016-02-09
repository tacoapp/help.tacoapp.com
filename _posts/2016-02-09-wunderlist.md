---
layout: page
title: "Wunderlist"
category: connectors
date: 2016-02-09 08:00:00
order: 118
---

# Setup

To connect Wunderlist with Taco, from the Connectors page, click
"Wunderlist." Wunderlist will prompt you to grant Taco's access. Approve
the access request and Taco will immediately retrieve tasks.


# Behavior

Taco imports up to 100 incomplete tasks and subtasks from all lists. Taco
tries to infer whether a task is part of a list to which only you have access,
or part of a shared list (within the bounds of how this is exposed in
Wunderlist).

Based on that, Taco shows all tasks on lists that only you have
access to, and only tasks assigned to you on shared lists.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g wu` (as in "go to
Wunderlist") to open Wunderlist in a new browser tab.
