---
layout: page
title: "Lighthouse"
category: connectors
date: 2013-07-27 10:30:13
---

# Setup

To connect Lighthouse with Taco, from the Connectors page, click
"Lighthouse." Taco will present a settings page like the one below.
Obtain a read-only API key per 
[Lighthouse Support](http://help.lighthouseapp.com/kb/api/how-do-i-get-an-api-token).

![Sync Lighthouse issues via API]({{ site.url }}/assets/images/connectors/lighthouse/settings.png)


# Behavior

By default, Taco imports all tickets which match this filter:

    responsible:me updated:"2 months ago" state:(new,open) sort:priority

This filter is appropriate for most Lighthouse environments. You may also
define your own filter, as shown in the screenshot above. See
[Lighthouse Support](http://help.lighthouseapp.com/kb/getting-started/how-do-i-search-for-tickets)).
