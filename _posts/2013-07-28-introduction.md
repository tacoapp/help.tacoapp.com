---
layout: page
title: "Introduction"
category: how-it-works
date: 2013-07-28 06:55:27
---


## What and why?

Taco helps you intentionally choose, confidently focus on, and
efficiently finish the tasks you already have. Taco brings all of the
tasks you have – from the services you already use – on to one screen.

Learn more on Taco's [Kickstarter listing](https://tacoapp.com/kickstarter)
(and video), our too-short-to-be-a-manifesto [manifesto](https://tacoapp.com/info/about),
or Leo Babauta on [The Daily Checklist](http://zenhabits.net/check/).


## Connectors

Taco works by interfacing with the task lists you already use. The world
doesn't need another way to create tasks, which is why you can't create
tasks in Taco.

Link the services you use and love by clicking the "Connectors" icon. On
[Connectors](https://tacoapp.com/connectors), choose a service. You'll
either be prompted to approve Taco's access (for services which support
OAuth) or be prompted for access information (such as an API key).

When a connector is authorized, Taco will display a message like this
and will immediately try to obtain related tasks:

!["Connector activated. We're trying to retrieve tasks right now."]({{ site.url }}/assets/images/sync-message.png)

See the "Connectors" sidebar section for details about each connector's
sync behavior.


## The Basics

Here's what Taco does. 

**Important**: Like Taco itself, this document is evolving and includes
freeform notes.

### Drag and drop ("I'm ready to work on this now")

### Sync

### Hide ("I can't act on this")

Often other people set priorities for us, or there's simply items you
can't actually make progress on right now (but aren't able to remove). 
Click "Hide" to remove them from the Taco's typical view. You can see
hidden tasks by clicking the "Toggle Hidden Tasks" menu icon.

### Top ("On my radar")

Just learn information which made a task much more important than it
was? Click "Top" to move it to the top of "Up next."

### Print

Create a PDF with all tasks, like to print, save, or email it.

### Email

Send yourself an email containing "Up next" items (like the daily punchlist).

### Settings

Edit [Settings](https://tacoapp.com/connector), including connectors,
email summary frequency, and themes.

<a name="themes"></a>
#### Themes

We want Taco to be an environment you love to work in (or better, many
such environments). To that end, Taco provides a handful of custom
backgrounds as themes. Choose one or provide your own.

As an advanced option, you can provide your own background image or
color. To provide a background image, add `?background=` and the URL to
the image. For example:

    https://tacoapp.com/tasks?background=http://the.url.com/wallpaper.png

[This URL](https://tacoapp.com/tasks?background=http://otife.com/wp-content/uploads/2013/04/HD-wallpaper-Otife-abstract-tardis.jpg)
loads Taco with a different background. Images can live on any Web site,
such as these [free hosts](https://www.google.com/search?q=free+image+hosting)).

To provide a solid color instead of a background image, add `?bgcolor=`
and the 6-digit RGB ("HTML color") code, like `FF00FF`. For example:

    https://tacoapp.com/tasks?bgcolor=22884F

Here are examples with [green](https://tacoapp.com/tasks?bgcolor=22884F), 
[orange](https://tacoapp.com/tasks?bgcolor=A64D00), and 
[blue](https://tacoapp.com/tasks?bgcolor=2A4580). To choose a color, try 
[Color Scheme Designer](http://colorschemedesigner.com/). 

To disable distinctive backgrounds, provide a neutral color like
[gray](https://tacoapp.com/tasks?bgcolor=444444).

Once you've settled on a theme that you like, bookmark its URL to use it
on an ongoing basis. This may become easier.

#### Email summary

Start the day out right with a punchlist of where you left off.  Taco
can email you what's up next every weekday, every day, or only on
Mondays. We'd put a joke about [work-life balance](http://en.wikipedia.org/wiki/Work%E2%80%93life_balance#Consequences_of_an_Imbalance)
here if we had one.


#### Keyboard shortcuts

#### App Icon

For users of [Fluid](http://fluidapp.com/) and other 
[site-specific browsers](http://en.wikipedia.org/wiki/Site-specific_browser#Software),
[here]({{ site.url }}/assets/images/taco-icon-500x500.png) is a 500x500
pixel icon.

### Non-Features

#### Automatic refresh

Taco doesn't automatically refresh at all. That decision began as a way
to be considerate of Google Tasks' API request limit, but after adding
additional services, we tried auto-syncing with other services. The
surprise: Troy really didn't care for tasks shifting underneath him.

Though an automatic refresh sounded really useful, trying it made Troy
realize that the unique thing about Taco is that it's entirely my own
preferences, decoupled from any others. Taco's stable, all-about-me
priority was my escape valve from other people's changes: I know nothing
will move unless I do it.

(Tangent: completing a task fell into the same "I thought I'd want it"
bucket. Turned out that visiting the underlying service to click "Close"
feels like a golf ball going into a hole - not something golfers think
of as a distraction! Usually there's task-specific notes to add anyway.)
