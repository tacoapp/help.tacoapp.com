---
layout: page
title: "UserVoice"
category: connectors
date: 2013-09-28 15:44:10
order: 117
---

# Setup

To connect UserVoice with Taco, from the Connectors page, click "UserVoice."
Taco will present a settings page like this one:

![UserVoice site subdomain]({{ site.url }}/asset/images/connectors/uservoice/subdomain.png)

Enter the site name of your UserVoice installation. For example, if your 
UserVoice site is at `acme.uservoice.com`, enter: `acme`

Click "Continue" and UserVoice will present an approval screen:

![Sync UserVoice tickets via OAuth]({{ site.url }}/assets/images/connectors/uservoice/oauth.png)

Click "Allow access" to approve Taco's access.


# Behavior

Taco imports up to 100 tickets which are 
[open](http://feedback.uservoice.com/knowledgebase/articles/175-where-s-the-pending-status-for-tickets-)
and assigned to you.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g us` (as in "go to
UserVoice") to open UserVoice in a new browser tab.
