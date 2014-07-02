---
layout: page
title: "TeamworkPM"
category: connectors
date: 2013-09-16 16:15:02
order: 100
---

# Setup

To connect Teamwork Project Manager (PM) with Taco, from the Connectors
page, click "TeamworkPM." Taco will present a settings page like the one
below. On the TeamworkPM "My Details" page, enable the API and obtain
your API token per [TeamworkPM Support](http://developer.teamwork.com/enabletheapiandgetyourkey).

If your Teamwork site uses a [custom domain](http://docs.teamwork.com/article/175-create-a-custom-domain-for-your-installation)
like `clients.acmeanvils.com`, it still has a corresponding name within
`.teamwork.com` (such as `acme.teamwork.com`). When configuring Taco,
use the `acme` part, or just ask us if you don't know it.

Once you have the API key, provide it to Taco:

![Sync TeamworkPM issues via API]({{ site.url }}/assets/images/connectors/teamworkpm/settings.png)


# Behavior

Taco imports all non-completed tasks which are assigned to you, from across all projects.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g te` (as in "go to
TeamworkPM") to open TeamworkPM in a new browser tab.
