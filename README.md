# Keyboard Layout

- [Flash K3 Pro Firmware](https://www.keychron.com/blogs/archived/k3-pro-factory-reset-and-firmware-flash)
- [Keychron Firmwares](https://www.keychron.com/pages/firmware)
- [VIA HowTo](https://www.keychron.com/blogs/archived/how-to-use-via-to-program-your-keyboard)
- Keyboard has four layers (0-3):
  - 0: Mac/iOS default layer 
  - 1: Mac/iOS mod layer 
  - 2: Windows/Android default layer 
  - 3: Windows/Android mod layer 

## Use layout

- [allow read/write access to keyboard](https://bbs.archlinux.org/viewtopic.php?pid=2099248#p2099248): `sudo chmod a+rw /dev/hidraw*`
- visit usevia.app
- authorize device
- enable design tab: config -> show design tab
- load layout: design tab -> load draft definitions -> select layout json

