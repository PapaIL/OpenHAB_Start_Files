# OpenHAB_Start_Files

This is a package of OpenHAB 2 config files to get beginners started.

These files relate to the DIY Home Automation hardware & software at this location.
	http://homeautomation.proboards.com/
		especially http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
		
These files should be installed after OpenHAB 2 is installed & before one would use the browser link to enter the PaperUI dashboard.  In this way, as I recommend, the configurations can be accomplished through configuration text files that end in .cfg

This version of addons.cfg should provide all the Add-Ons that OpenHAB needs for the DIY Home Automation projects.

This version of mqtt.cfg should help set up OpenHAB to use the Mosquitto message broker to communicate between the DIY Home Automation components. (One must also install the Mosquitto service on the same computer that hosts OpenHAB.)

http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
The three "My" files (My.items, My.rules, My.sitemap) are sample OpenHAB config files that particularly relate to this project to build one's first DIY Home Automation network of a Gateway & a node that communicate with RFM69 radios & the Gateway bridges communication between the node & OpenHAB.

To the basic OpenHAB icon set, comfort_level.svg adds a display icon for the first DIY Home Automation network project.
		
There is a Linux bash script to download these files & copy them to the correct folders.
