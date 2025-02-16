# OctoPrint-Print-Queue

This plugin proves a way to print one object after another. After printing an object it will run a gcode script (that you provide) to clear the print bed, and then will start printing the next object in the queue.

This plugin only works if you have some way of automaticaly clearing your print bed. If the print does not successfully clear before starting the next one, all manner of Bad Things are likely to happen.

Installing this plugin (walkthrough):

Open your Octoprint UI and go to into settings (the wrench icon in the top right).
In the left menu, scroll down and open Plugin Manager.

Click on the get more button (top right). You may have to enter your octoprint password at this point.
Scroll to the bottom of the window (using the outer scrollbar) until you see the "...From URL" field.

Paste the link "https://github.com/michaelnew/Octoprint-Print-Queue/archive/master.zip" into the From URL box (without the " " on the outsides, so https:// etc) and hit Install.

Once the plugin finishes installing, you will see "Done!" pop up. Go ahead and restart your octoprint setup (in my case turning my raspi off and on).
Reload your page, and you should be able to find the Print Queue plugin either on the taskbar at the top, or under the dropdown at the end of the taskbar.

In terms of using the plugin, here "https://youtu.be/NZgjl8W5yrE" is a video with a mini showcase of how to use the UI (its plugin 1). You will have to come up with the gcode yourself, but there is plenty of documentation on the interent. Good luck!