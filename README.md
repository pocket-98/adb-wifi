# adb-wifi
Script to turn on and off wireless adb debugging from android device (requires root)

## Usage
* as root mount `/system/` as read-write and move the script to `/system/bin/`
* as root use `adb-wifi <port|status>` to set the port for wireless adb, or use the words `on` or `off` to default to ports 5555 and -1 respectively.
* run `adb-wifi` to see what port debugging is enabled on (-1 means off)
