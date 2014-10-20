---
layout: page
title: "OmniFocus"
category: connectors
date: 2013-11-04 06:36:18
order: 57
---

# Setup

To connect OmniFocus (via [Omni Sync Server](http://www.omnigroup.com/support/omnifocus-omni-sync-server))
with Taco, from the Connectors page, click "OmniFocus." Taco will
present a settings page like the one below. Provide your Omni Sync
Server credentials.

## Account name

Omni Sync Server relies on your account name (username), which is 
usually *not* your email address. To find your Omni Sync Server account 
name, visit [Manage Omni Sync Server](https://manage.sync.omnigroup.com/manage):

![Omni Sync Server Account Name]({{ site.url }}/assets/images/connectors/omnifocus/account_name.png)

# Behavior

Taco imports all active (started and not paused) tasks from across all 
contexts. For more granular control, consider 
[filters](../how-it-works/the-rest.html#filters). Taco can filter by
project name, context name, inbox or flagged status, and more. For
example:

    "Important Project" OR "Home" OR "Flagged" OR "Inbox"

## Links

Clicking a task label will view the task in OmniFocus locally.
OmniFocus will be started if it is not already running.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g of` (as in "go to
OmniFocus") to open OmniFocus on your desktop. The "Inbox" perspective
will be shown.
