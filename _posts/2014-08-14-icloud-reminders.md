---
layout: page
title: "iCloud Reminders"
category: connectors
date: 2014-08-14 10:50:02
order: 46
---

## Temporarily unavailable

**Important**: iCloud Reminders are currently unavailable due to a change in
Apple's iCloud security policy. The Taco team is optimistic that Taco can still
work with iCloud Reminders at some point, but we want to see iCloud become
more stable (or ideally, provide a real API) before releasing and supporting
another integration.

--

To connect iCloud Reminders (also used for the iOS Reminders and OS X
Reminders apps) with Taco, from the Connectors page, click "iCloud
Reminders."

Taco will present more specific instructions for
[sharing](http://support.apple.com/kb/PH12516) reminder lists with Taco.
Provide Taco with the email address of your
[Apple ID](http://support.apple.com/kb/HT5625) (iCloud, App Store, and
iTunes) account.

# Behavior

Taco imports all reminders in the reminder list(s) you share with Taco.

## Notes

If you rename a list after sharing it with Taco, Taco will still show
the old list name when hovering over a task. To update the list name,
un-share and re-share it to `icloud@tacoapp.com`.

## Options

If you set "Remind me on" dates for tasks that aren't relevant until
then, Taco ignore tasks with "Remind me on" dates set (until the day
before the reminder).

Also, Taco can ignore recurring tasks until the day before the next
occurrence.

These options are shown in the connector settings and are enabled by
default.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g ic` (as in "go to
iCloud") to open iCloud in a new browser tab.
