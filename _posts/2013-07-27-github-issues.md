---
layout: page
title: "GitHub Issues"
category: connectors
date: 2013-07-27 10:30:13
---

# Setup

To connect GitHub Issues with Taco, from the Connectors page, click
"GitHub Issues." GitHub will present a confirmation page like this:

![Sync GitHub Issues with OAuth]({{ site.url }}/assets/connectors/github-issues/oauth.png)


# Behavior

Taco imports up to 100 GitHub Issues which are assigned to you, from
across all repos.

Note that Taco has as little access as possible in order to see Issues.
As shown in the permission screen above, it's still more access than we
want. We have contacted GitHub to suggest an OAuth access [scope](http://developer.github.com/v3/oauth/#scopes) 
which may only access Issues.
