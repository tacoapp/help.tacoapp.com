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

### Ensure Taco has access

First, visit RTM's [General Settings](https://www.rememberthemilk.com/home). 
Turn on "[Private Addresses](http://www.rememberthemilk.com/help/?ctx=feeds.rss.privateaddress)" 
if it isn't already enabled:

![Remember The Milk Private Addresses setting]({{ site.url }}/assets/images/connectors/remember-the-milk/private-addresses.png)

### Choose tasks (optional)

Remember The Milk creates an "All Tasks" list for you. Taco can use that
list and import all of your incomplete tasks. 

Alternatively, to import a different set of tasks, like only those 
due prior to now, create an RTM [Smart List](https://www.rememberthemilk.com/help/?ctx=iphone.smartlists.addsmartlist) 
and point Taco at that list.

Smart Lists can use any RTM search, like `dueBefore:now` or `list:"Work
stuff"`. See [Smart List](https://www.rememberthemilk.com/help/?ctx=iphone.smartlists.addsmartlist) docs.
Taco automatically ignores completed tasks

### Obtain URL

Second, obtain the "Atom URL" from your RTM "All Tasks" tab/list or any 
other RTM list. (Have an older RTM account with no "All Tasks" tab? Here's 
[how to create it](https://www.rememberthemilk.com/forums/help/10179/)).

Once on the "All Tasks" list (or the list you would like Taco to use), copy 
its Atom URL from the link shown in the screenshot below.

#### About the Atom URL

<a name="credentials"></a>
**Important**: this URL will end with `tok` followed by 50 or more random 
letters. This is the API key and it allows Taco to obtain your tasks. When 
you copy the URL, it should look like this (but with far more random letters 
after the `?tok=`):

    https://www.rememberthemilk.com/atom/bob.jones/1234/?tok=GgUGhn09t3Kz*3Qe

![Remember The Milk Atom/RSS URL]({{ site.url }}/assets/images/connectors/remember-the-milk/atom.png)

After copying the URL, paste it into the Taco's RTM settings page. 

# Behavior

Taco imports all incomplete tasks in the Remember The Milk list 
which you chose (such as "All Tasks"). Since RTM lists can use 
any RTM search, Taco can
retrieve any set of tasks.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g re` (as in "go to
Remember The Milk") to open Remember The Milk in a new browser tab.
