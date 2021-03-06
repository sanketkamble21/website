---
layout: docs
title: Auto Reloading the Browser Window When Changes Are Made | Pattern Lab
heading: Auto Reloading the Browser Window When Changes Are Made
---

{% capture m %}

Rather than manually refreshing your browser when your patterns or CSS change, Pattern Lab auto-reloads your browser window for you using [BrowserSync](http://www.browsersync.io/).

Auto-reloading is a behavior that is done in concert with file watching. You can read more about how these two features work together [here](/docs/advanced-auto-regenerate.html#node).

## How to Start and Connect to Pattern Lab with BrowserSync

Running 'gulp patternlab:serve' or 'grunt patternlab:serve' from the command line of your working directory will start up Pattern Lab with BrowserSync and launch [http://localhost:3000](http://localhost:3000) in your default browser.

## How to Stop the Server

To stop watching and serving files on Mac OS X and Windows you can press`CTRL+C` in the command line window where the process is running.

<strong>The PHP version of Pattern Lab is being deprecated in favor of a new unified Pattern Lab core. <a href='./php/advanced-reload-browser'>The PHP docs for this topic can be viewed here.</a></strong>

{% endcapture %}
{{ m | markdownify }}
