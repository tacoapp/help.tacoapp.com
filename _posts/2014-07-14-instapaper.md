---
layout: page
title: "Instapaper"
category: connectors
date: 2014-07-14 10:50:02
order: 48
---

To connect Instapaper with Taco, from the Connectors page, click
"Instapaper." Taco will present a settings page.

### Obtain Instapaper RSS URL

All Instapaper folders are available via RSS. To find the URL, on 
[instapaper.com](https://instapaper.com/), browse to the folder with 
your must-read documents. You can also create a new folder for them.

**Important**: Don't add your main Instapaper folder to Taco. Think of
Taco as the place to work through the very few documents you actually
need to read, not the many which you simply might enjoy reading.

#### View Source

While on the folder's document list, view the HTML source in your Web
browser. In Chrome, that's View -> Developer -> View Source. Search 
the HTML for `rss`. You'll find a line like this near the start:

```
<link rel="alternate" type="application/rss+xml" title="RSS" 
href="/folder/1234567/rss/234567/u9awfuhoewafh3fwea" />
```

Copy the full URL and paste it into Taco's settings page. For example:

    https://www.instapaper.com/folder/1234567/rss/234567/u9awfuhoewafh3fwea


# Behavior

Taco imports all documents saved to the Instapaper folder.

## Keyboard shortcut

While using Taco, press the keyboard shortcut `g in` (as in "go to
Instapaper") to open Instapaper in a new browser tab.
