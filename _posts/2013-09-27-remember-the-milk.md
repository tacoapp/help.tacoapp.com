---
layout: page
title: "Remember The Milk"
category: connectors
date: 2013-09-27 10:12:00
order: 80
---

# Setup

To connect Remember The Milk with Taco, from the Connectors page, click
"Remember The Milk." Taco will present a settings page like the one
below.

First, enable "[Private Addresses](http://www.rememberthemilk.com/help/?ctx=feeds.rss.privateaddress)" 
in Remember The Milk.

Second, obtain the "Atom URL" from your Remember The Milk "All Tasks"
tab/list (or any other list). (Have an older RTM account with no "All
Tasks" tab? Here's 
[how to create it](https://www.rememberthemilk.com/forums/help/10179/)).

Once on the "All Tasks" list or the list you would like Taco to use,
copy its Atom URL from the link shown in this screenshot:

![Remember The Milk Atom/RSS URL]({{ site.url }}/assets/images/connectors/remember-the-milk/atom.png)

After copying the URL, paste it into the Taco's Remember The Milk
settings page. The URL will contain an API key, which enables Taco to
obtain your tasks. For example:

    https://www.rememberthemilk.com/atom/user.acct/1234567/?tok=a-very-long-code


# Behavior

Taco imports all tasks in the list which you chose (such as "All
Tasks"). To import a different set of tasks, like only those due prior
to now, create an RTM 
[Smart List](https://www.rememberthemilk.com/help/?ctx=iphone.smartlists.addsmartlist) 
and point Taco at that list. Smart Lists can use any RTM search,
like `dueBefore:now`.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g re` (as in "go to
Remember The Milk") to open Remember The Milk in a new browser tab.
