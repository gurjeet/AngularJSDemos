# AngularJS Demos

This repository contains examples that were shown in Dan Wahlin's presentaition
"AngularJS Fundamentals In 60-ish Minutes", plus a few improvements.

First, watch that video to get a handle on the "Big Picture" of AngularJS, and
why it's such a big deal.

Then, to see the demos, simply extract this on your computer and open the DemoList.html
file in your browser.

Then, FTW, tinker with the HTML/code in the files.

The Visual Studio 2012 solution is designed to run with IIS Express. To open it
follow these steps:

1. Start Visual Studio 2012
2. Select File --> Open Website and select the AngularJSDemos folder
3. Right-click on the website project and select Use IIS Express from the menu

You should be all set.

If you don't want to use Visual Studio you can still run everything but you'd
possibly need to update the urlBase path in DemoList.html since it expects
`DemoPartials` and  `app` directories to be off the root of whatever site you run.
