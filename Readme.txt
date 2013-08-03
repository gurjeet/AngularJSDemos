The Visual Studio 2012 solution is designed to run with IIS Express. To open it follow these steps:

1. Start Visual Studio 2012
2. Select File --> Open Website and select the AngularJSDemos folder
3. Right-click on the website project and select Use IIS Express from the menu

You should be all set.

If you don't want to use Visual Studio you can still run everything but you'd possibly need
to update the urlBase path in DemoList.html since it expects DemoPartials to be off the root
of whatever site you run.