# home-assistant
I run HA on an old gaming rig I stripped down. It's overkill, but it was a spare pc gathering dust, and it's not too bad on power consumption since it's idling all the time. It's running proxmox on bare metal, debian VM for docker. HASS.IO in one of those docker containers. I pretty much followed diybrad's guide to a t:

https://diyfuturism.com/index.php/2018/03/20/pi-to-nuc-part-1-migrating-hass-io-to-a-virtual-machine-proxmox-docker/


**hubs:**
* hue
* aotec z-wave stick
* xiaomi
* lutron pro hub

**Hardware:**
* in-wall switches  x3
* in-wall dimmers   x2
* in-wall fan control x1 (not currently installed, new apt w/o cieling fans)
* human body sensors
* temperature/humidity sensors  x3
* buttons x4
* pico remotes  x3
* Schlage BE469 z-wave deadbolt lock

**upcoming projects:**
* work on floorplan
* ibeacons - set them up in parking space and at front door for a door unlock automation
* scheduling temperature in node-red dashboard ui
