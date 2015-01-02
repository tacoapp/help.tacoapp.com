---
layout: page
title: "Quick Start"
category: how-it-works
date: 2013-07-28 06:55:27
order: 0
---

On Taco's [Connectors][] page, link the services you use and love.
Takes about 10 seconds.

### How's this work?

Choose a service. You'll either be prompted to approve Taco's access or
be prompted for access information (such as an API key).

When a connector is authorized, Taco will display a message like this
and then fetch your tasks:

!["Connector activated. We're trying to retrieve tasks right now."]({{ site.url }}/assets/images/sync-message.png)

Many connectors can filter tasks too, like to only retrieve certain
projects. For details, see [Filters][] or each connector's help page.


## Using Taco

### Ready to work? Just drag & drop

Just click a task and drag it from For Later to Up Next, or vice versa.
It's that simple.

<a name="complete"></a>
### Done? Complete a task

For many services, Taco can update the service when you finish a task.
For example, Taco can archive an email in your Gmail inbox and can mark
a Basecamp to-do as complete.

To mark a task complete, hover over the task and click the checkbox
which appears. 

![Complete a task]({{ site.url }}/assets/images/complete.png)

A prompt will ask whether Taco should update the service
(if available) or simply hide the task on Taco.

![Complete or hide a task]({{ site.url }}/assets/images/completion-popover.png)

### Updating tasks: Sync

Click the Sync icon to tell Taco to update its data from your connected
services. In 10-15 seconds, you'll see the updated information roll in.

Taco automatically syncs roughly hourly while you're active and daily
when you're not.

### Top

Did one task suddenly become much more important than it was? Click
"Top" to move it to the top of "Up next."

### Focus! Hide the sidebar

Once you've chosen 1-3 things to do, hide "For Later." Either hit `\`
(backslash) or click the arrow at the far left edge of the screen.

To display "For Later" again, do the same thing. Taco remembers your
last-used option.

![Hide sidebar]({{ site.url }}/assets/images/focus-mode.gif)

### See task details

To see additional information about most tasks, such as a project name,
due date, status, or sender email address, hover over the text label of
the task. You'll see a box like this:

![Hover to see extra information]({{ site.url }}/assets/images/hover-attributes.png)

These attributes are also [searchable](the-rest.html#find-as-you-type-search),
like to see only tasks from a certain service or project within that 
service.

### Can't act on a task? Hide it

Often other people set priorities for us, or there's simply items you
can't actually make progress on right now (but aren't able to delete or
complete). Clicking a task's checkbox can also be used to hide a task in
Taco, removing it from Taco's typical view.

To see hidden tasks, click the "Toggle Hidden Tasks" menu icon in the
upper right corner. The icon looks like an eye.

### Print

Create a PDF with all tasks, like to print, save, or email it.

### Email

Send yourself an email containing "Up next" items (like the daily
punchlist). Taco can also send this every day or week; see 
[Email Settings](https://tacoapp.com/connectors#email-notifications-settings).


## Settings

Visit [Settings](https://tacoapp.com/connectors) to add connectors or
change preferences.

### Email summary

Start the day out right with a punchlist of where you left off. Taco
can email you what's up next every weekday, every day, or only on
Mondays. We'd put a joke about 
[work-life balance](http://en.wikipedia.org/wiki/Work%E2%80%93life_balance#Consequences_of_an_Imbalance)
here if we had one.

To enable it, visit [Email Settings](https://tacoapp.com/connectors#email-notifications-settings).

![Email options]({{ site.url }}/assets/images/email-options.png)

<a name="themes"></a>
### Themes

We want Taco to be an environment you love to work in, so Taco provides
a handful of sharp-looking backgrounds. Choose one on
[Theme Settings](https://tacoapp.com/connectors#themes-settings).

#### Custom theme

To provide your own theme, provide the URL to an image of any size
or choose a solid color.

To disable distinctive backgrounds entirely, choose a neutral color
like white, gray, or black.

Ready to geek out a bit? Keep reading [The Rest](the-rest.html).

[Connectors]: https://tacoapp.com/connectors
[Filters]: the-rest.html#filters
