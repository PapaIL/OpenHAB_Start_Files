# OpenHAB_Start_Files

This is a package of OpenHAB 2 config files to get beginners started after OpenHAB is installed on a Windows computer or a Linux computer (including Raspberry Pi).

These files relate to the DIY Home Automation hardware & software at this location:
	http://homeautomation.proboards.com/
		especially http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
		
These files should best be installed just after OpenHAB 2 is installed & just before one would use the browser link to enter the PaperUI dashboard.  In this way, as I recommend, the configurations can be accomplished through configuration text files that end in .cfg

Caution:  If you install these files in their expected OpenHAB2 folders, they may overwrite existing OpenHAB config files.  If your existing files have important entries that you do not want to lose, save copies of the files elsewhere where you can find them.

This version of addons.cfg should provide all the Add-Ons that OpenHAB needs for the DIY Home Automation projects.

This version of mqtt.cfg should help set up OpenHAB to use the Mosquitto message broker to communicate between the DIY Home Automation components. (One must also install the Mosquitto service on the same computer that hosts OpenHAB.)

http://homeautomation.proboards.com/thread/222/building-rfm69-automation-network-beginners
The three "My" files (My.items, My.rules, My.sitemap) are sample OpenHAB config files that particularly relate to the above project of building one's first DIY Home Automation network of a Gateway & a node that communicate with RFM69 radios & the Gateway bridges communication between the node & OpenHAB.

To the basic OpenHAB icon set, comfort_level.svg adds a display icon for the first DIY Home Automation network project.
		
A Windows batch script & a Linux bash script are being developed to download these files & copy them to the correct folders.
