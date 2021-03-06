# OpenHAB_Start_Files

This is a package of OpenHAB 2 config files to get beginners started after OpenHAB is installed on a Windows computer or a Linux computer (including Raspberry Pi).

These files relate to the DIY Home Automation hardware & software at this location:
	http://homeautomation.proboards.com/
		especially http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
		
These files should best be installed just after OpenHAB 2 is installed & just before one would use the browser link to enter the PaperUI dashboard. (One might also install these files if they want to start fresh on configuring OpenHAB.) In this way, as I recommend, the configurations can be accomplished through configuration text files that end in .cfg   

Caution:  If you install these files in their expected OpenHAB2 folders, they may overwrite existing OpenHAB config files.  If your existing files have important entries that you do not want to lose, save copies of the files elsewhere where you can find them.

This version of addons.cfg should provide much of the Add-Ons that OpenHAB needs for the DIY Home Automation projects. However, if you want to use openhab cloud, you need to add that to misc =

This version of mqtt.cfg should help set up OpenHAB to use the Mosquitto message broker to communicate between the DIY Home Automation components. (One must also install the Mosquitto service on the same computer that hosts OpenHAB.)

http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
The three "My" files (My.items, My.rules, My.sitemap) are sample OpenHAB config files that particularly relate to the above project of building one's first DIY Home Automation network of a Gateway & a node that communicate with RFM69 radios & the Gateway bridges communication between the node & OpenHAB.

To the basic OpenHAB icon set, comfort_level.svg adds a display icon for the first DIY Home Automation network project.

classic.zip, extract its files to OpenHAB's \icons\classic folder.  For your OpenHAB User Interface display, this gives you several added icons, many from JimKernsJr & some from me.

Put weather.cfg in OpenHAB's \services folder.  With Notepadd++, open it for editing.  Find 3 lines that have "Replace this ..." after =. Replace everything after the = with the requested info.

Other files starting with "weather" need OpenHAB's Weather binding installed & edits in weather.cfg  See here for help with that: http://homeautomation.proboards.com/thread/191/display-weather-info-openhab-interface

weather_English.items & weather_Metric.items give you several weather items to work with & show you examples. Use only one of them in OpenHAB's \items folder or they will conflict. You can open & edit them with Notepad++.  Use information at http://homeautomation.proboards.com/post/1814/thread, including the official OpenHAB documentation references, to help you make changes.

weather.rules combines some weather items so they can display in one screen slot.  Weather.sitemap displays the weather data obtained from weather items & weather rules.
		
At http://homeautomation.proboards.com/post/3337/thread is a Windows batch script to download some of these files & copy them to the correct folders. A Linux bash script is being developed to do the same.
