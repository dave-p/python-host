# python-host

# What is the SwitchBot opensource project?
[SwitchBot](https://www.switch-bot.com) is a smart IoT robot to mechanically control all your switches and buttons. You can control the bot by your smartphone app ([iOS](https://itunes.apple.com/app/SwitchBot/id1087374760?mt=8) or  [Android](https://play.google.com/store/apps/details?id=com.theSwitchBot.SwitchBot), SwitchLink, or other platform based on our open APIs.

This project aims to provide a super light-weight solution to control your SwitchBot on [Raspberry Pi](https://www.raspberrypi.org)/[OpenWRT](https://openwrt.org/) or any other Linux based board.

This version has been tested on Raspberry Pi OS running Python 3.9.

# How to Install?

## On Raspberry Pi
You will need:
  -  A Raspberry Pi Zero W, Zero 2 W, 3, 4, or 400.
  -  A SwitchBot.
  -  An SD Card with a fresh install of Raspberry Pi OS.

## Installation
Boot your fresh Pi and open a command prompt.

To install the required dependencies on Debian 11 "Bullseye", Raspberry Pi OS or Ubuntu 21.10 or later:

```sh
sudo apt install python3-bluez
```

Type `python3 switchbot_py3.py -h/--help` for usage tips.
```
eg: sudo python3 switchbot_py3.py -d xx:xx:xx:xx:xx:xx -c close
```

Enjoy :)

# References

[SwitchBotAPI-BLE](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE) 

- [Bot BLE open api](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/bot.md)

- [Meter BLE open api](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/meter.md)

- [Curtain BLE open api](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/curtain.md)

- [Contact Sensor BLE open api](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/contactsensor.md)

- [Motion Sensor BLE open api](https://github.com/OpenWonderLabs/SwitchBotAPI-BLE/blob/latest/devicetypes/motionsensor.md)

# Thanks to contributors
[@BlackLight](https://github.com/BlackLight)

[@rcmdnk](https://github.com/rcmdnk)

[@tony-wallace](https://github.com/tony-wallace)


# Community

[SwitchBot (Official website)](https://www.switch-bot.com/)

[Facebook @SwitchBotRobot](https://www.facebook.com/SwitchBotRobot/) 

[Twitter @SwitchBot](https://twitter.com/switchbot) 
