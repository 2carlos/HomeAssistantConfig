# My Home Assistant Config
I run HA on an old pc I had gathering dust. It runs proxmox with 2 VMs:
* HASS.IO
* NAS4FREE for my personal media
* LxC container for Plex

I used this guide to set up Hass.io on top of proxmox:

https://diyfuturism.com/index.php/2018/03/20/pi-to-nuc-part-1-migrating-hass-io-to-a-virtual-machine-proxmox-docker/


**Hubs:**
* hue
* VeraPlus
* xiaomi
* lutron pro hub
* Harmony Companion Hub

**Devices:**
* in-wall switches  x6
* in-wall dimmers   x2
* light bulbs x4
* in-wall fan control x1 (not currently installed, new apt w/o cieling fans)
* human body sensors x3
* temperature/humidity sensors  x3
* door sensor x1
* aqara buttons x4
* pico remotes  x3
* Schlage BE469 z-wave deadbolt lock
* iBeacons x4

**Upcoming Projects:**
* morning routine

**Cool Automations**
Nearest city instead of 'away' for device_tracker: In node-red, I capture the lat/long from the HA ios app, pass it to OpenWeatherMap to get some data, including the nearest city. Then I update a device_tracker with the name of the nearest city.
