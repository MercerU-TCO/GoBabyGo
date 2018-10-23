---
title: Page Layouts 
layout: topic
---

# Page layouts

The following page layouts are supported by this project. They are based on (derived from) the Cayman theme.

## default

The _default_ layout from the Cayman theme. It was modified to remove the Google APIs fonts. This gives you just the boring fonts that work when the site is hosted on a server that is not connected to the Internet. Upside: makes page loads very low overhead (and fast).

## topic

The _topic_ layout is the standard page layout for generic content pages.

## topicTask

The _topicTask_ layout is similar to (and derived from) the _topic_ layout. It should look just like a _topic_ page, except it provides a link to the task list page at the top and bottom of the page. The page these links should open is defined in the front matter by assigning  the **mainTaskPage** variable to point to the html page of the task list.

