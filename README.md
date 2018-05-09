# home-assistant
I run HA on an old pc I had gathering dust. It runs proxmox with 2 VMs:
* debian for docker that runs HASS.IO, node-red, & Plex
* NAS4FREE for my personal media

see here for the guide I used to set up this config:

https://diyfuturism.com/index.php/2018/03/20/pi-to-nuc-part-1-migrating-hass-io-to-a-virtual-machine-proxmox-docker/


**Hubs:**
* hue
* aotec z-wave stick
* xiaomi
* lutron pro hub
* Harmony Companion Hub

**Hardware:**
* in-wall switches  x6
* in-wall dimmers   x2
* in-wall fan control x1 (not currently installed, new apt w/o cieling fans)
* human body sensors x3
* temperature/humidity sensors  x3
* door sensor x1
* aqara buttons x4
* pico remotes  x3
* Schlage BE469 z-wave deadbolt lock

**Upcoming Projects:**
* work on floorplan
* customUI tiles
* ibeacons - set them up in parking space and at front door for a door unlock automation
* scheduling temperature in node-red dashboard ui
