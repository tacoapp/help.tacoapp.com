---
layout: page
title: "GitHub Issues"
category: connectors
date: 2013-07-27 10:30:13
order: 35
---

# Setup

To connect GitHub Issues with Taco, from the Connectors page, click
"GitHub Issues." GitHub will present a confirmation page like this:

![Sync GitHub Issues with OAuth]({{ site.url }}/assets/images/connectors/github-issues/oauth.png)


# Behavior

Taco imports up to 100 GitHub Issues which are assigned to you, from
across all repos.

### Access and private repos

Taco has as little access as possible in order to see Issues. As shown in
the permission screen above, the absolute minimum access is still more access
than we want. We have contacted GitHub to suggest an OAuth access
[scope](http://developer.github.com/v3/oauth/#scopes) which may only access
Issues, not code.

To see what Taco can currently access, visit [GitHub Applications](https://github.com/settings/applications)
and click the "Taco" text title. This will show whether Taco can see
both public and private repos as well as any organizations which have
organization-wide restrictions.

#### Only public repos

If you absolutely cannot grant access to private repos, but still want
to use Taco for Issues on public repos, follow the same instructions
above. When you reach the `github.com` approval screen, edit the
`github.com` URL and change `scope=repo` to `scope=public_repo`
(from [scopes](https://developer.github.com/v3/oauth/#scopes)).
Access the modified URL with the other parameters unchanged. GitHub
will prompt you to grant access to only public repos.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g gi` (as in "go to
GitHub Issues") to open GitHub Issues in a new browser tab.
