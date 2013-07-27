--
layout: page
title: "Pivotal Tracker"
category: connectors
date: 2013-07-27 10:30:13
order: 70
---

# Setup

To connect Pivotal Tracker with Taco, from the Connectors page, click
"Pivotal Tracker." Taco will present a settings page like the one below.
Obtain an API key from your Pivotal Tracker [Profile](https://www.pivotaltracker.com/profile) 
page (accessible via the drop-down menu under your name in the top right corner).

![Sync Pivotal Tracker issues via API]({{ site.url }}/assets/images/connectors/pivotal-tracker/settings.png)


# Behavior

By default, Taco imports all stories which match this filter (from
across all projects):

    state:unstarted

This filter is appropriate for many Pivotal Tracker environments.
Depending on your workflow, this filter may be better:

    mywork:joe

where `joe` is your Pivotal Tracker username.

You may also define your own filter, as shown in the screenshot above.
See [Pivotal Tracker Help](https://www.pivotaltracker.com/help/faq#howcanasearchberefined).
