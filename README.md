# Description

CSS to partially revert Google's mobile design that went wide on desktop 1/16/20.

Unfortunately you cannot restore the actual page URLs instead of navigation breadcrumbs purely using CSS as far as I am aware. JS based tweaks are required, and out of the scope of what I'm willing to maintain.

# Instructions

Use one of the many Chrome extensions that allow persistent CSS tweaks for third party websites. (Stylus, Stylebot, Stylish, etc).

Create a new stylesheet for `https://www.google.com/search` and paste the contents of `revert.css` in this repository in.

**Note:** These changes may break at any time when Google pushes a style update. If you don't limit these tweaks to the Google results page only they may unpredictably affect other Google pages.
