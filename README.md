#Open SCT Flash
Reverse engineering SCT Flash products, mainly the X4.
** **



**Done**
* [Pull file system off device.](sdcard/NO NAME)
* [Document important integrated circuits and JTAG connectors.](docs/CircuitBoard.md)
* [Determine proper Sdcard file structure.] (docs/sdstructure.md)
* [Device Serial Number locations in software.] (docs/snlocations.md)
* [Stored VIN Number locations in software.] (docs/savedvin.md)
** **


**To Do / Goals**

* Determine if the difference in 7015 (Ford) and 7215 (DCX) is software based.
* Remove the VIN lock to one vehicle at a time.
* Enable flashing of multiple vehicles at a time without the need to return each one to stock.
* Upgrade the internal micro SD Card capacity to allow storage of more custom and pre-loaded tunes.
* Ability to specify a custom web server for updates.
* Monitor and log update communications between the handheld x4 and the update server.
* Create and run a web server to allow remote updating of files and firmware.
* Determine how to enable blocked features. 
** **


**To Do / Custom Features**

* Cooling fan on/off temperature adjustment.
* Disabling/Enabling Security features.
* Enable support for forced (Supercharger / Turbo) Induction.
* Enable use of wideband O2 sensor.
* Ability to disable Top Speed Limiter.
* Enable custom boot logo.
** **
