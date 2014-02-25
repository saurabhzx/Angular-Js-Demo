The Visual Studio 2012 solution is designed to run with IIS Express. To open it follow these steps:

1. Start Visual Studio 2012
2. Select File --> Open Website and select the AngularJSDemos folder
3. Right-click on the website project and select Use IIS Express from the menu

You should be all set.

If you don't want to use Visual Studio you can still run everything but you'll possibly need
to update the urlBase path in DemoList.html file since it expects the DemoPartials folder to be off the root
of whatever site you run. It'll definitely work with another editor - you may just have to tweak a path or two. :-)