
This is my Home Assistant Repository/Project.

I have been a user of Homeseer software for a number of years (2016).  I totaled up the other day what I had spent just on the software and plugins.  The total was $504.68.  This doesn't include hardware (computer, z-stick, or z-wave devices.)  Don't get me wrong I don't mind paying for software that works well and gets a job done.  But as projects like Home Assistant have matured the cost benefit ratio loses in my opinion. While Homeseer does a good job, I feel that Home Assistant can do as good or better.

First let me state that I am not a programmer nor a "system administrator".  I am a retired hobbyist who has fun trying to figure this stuff out and learn.  I get the extra added benefit of seeing immediate results to the work put in by seeing the devices I can control work and automations that make our life around the house more convenient.

I/We (my wife) have bought into the Amazon Alexa culture.  I currently have (1) Echo, (4) Dots, (1) Fire TV, (1) Fire TV Stick, (3) Fire Tablets.  

I have also bought into the Z-wave protocol.  The Z-Wave devices I have are numerous in-wall-mains powered dimmers (Homeseer), numerous in-wall-mains powered switches (Homeseer & Jasco), a Garage Door Controller (Go-Control), and numerous door/window sensors (Homeseer) installed and deployed.  I have an Everspring motion sensor, and Aeotec Mulitsensor Gen 5, and a Go Control Irrigation controller yet to deploy.

We have a Phillips Hue Ver 2 Hub and several Hue products.

I am running HassIO on a Raspberry Pi B+.  I have HACS installed, along with the Mosquitto Broker and Node-Red add-ins.

To a degree I have followed in @paulmona footsteps.  I, like he, have left all of my Z-wave devices setup in Homeseer and have Homeseer running.  I utilize the mcsMQTT plugin by Michael McSherry that publishes and subscribes Homeseer devices to the Mosquitto broker.  I then will control these devices via the Mosquitto broker from Home Assistant.

I am using the Code-OSS IDE to write my yaml files keeping them updated in git for version control.  I am then using the File Editor add-in to upload the most recent version of these files to my config directory.  

I am new to git as I am to Home Assistant so have yet to try and implement git directly from Home Assistant.