# adb-wifi
Script for to turn on and off wireless adb debugging from device (requires root)

##Usage
* on device open terminal and login as root
* use `adb-wifi <port|status>` to set the port for wireless adb, or use the words `on` or `off` to default to 5555 and -1 respectively.
* run `adb-wifi` to see what port debugging is enabled on (-1 means off)
