---
layout: page
title: "Salesforce"
category: connectors
date: 2014-07-09 15:44:10
order: 88
---

# Setup

To connect Salesforce.com with Taco and manage cases, from the
Connectors page, click "Salesforce."

## Salesforce editions

Only [these Salesforce editions/plans](https://help.salesforce.com/HTViewSolution?id=000005140&language=en_US) 
have API access, which is what allows Taco to retrieve your tasks.

## Authorize access

Salesforce will present a settings page like this one:

![Sync Salesforce cases with OAuth]({{ site.url }}/assets/images/connectors/salesforce/oauth.png)

Click "Allow" to approve Taco's access.


# Behavior

Taco imports up to:

* 250 cases which are not Closed and are assigned to you. This should be
  identical to the "My Open" view on salesforce.com's Cases tab.
* 250 tasks which are not Completed and are assigned to you.

## Closing cases and completing tasks

To mark a case closed or a task complete in Salesforce from within Taco,
click its checkbox in Taco. Taco will prompt you whether or not to
update Salesforce.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g sa` (as in "go to
Salesforce") to open Salesforce in a new browser tab.
