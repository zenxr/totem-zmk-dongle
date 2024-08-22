# eiga's zmk-config

This configuration was forked from [eigatech/zmk-config](https://github.com/eigatech/zmk-config)

### Table of contents
- [Dongle Flashing](#dongle-flashing)
- [ZMK Keymap Editor](#zmk-keymap-editor)
- [Shops and Useful links](#shops-and-other-useful-links)

## Hello

You probably reached this page by watching one of these [Ergo Split Keyb Videos](https://www.youtube.com/playlist?list=PL1E2ddJCbc13DvCGYXX9jVVX1BqNGKE5D).

This repository hosts zmk-configs as seen in the YouTube videos linked above.

Additionally, this repository contains alternative configurations meant to be used with an extra controller acting as a dongle. Pease refer to the [Dongle Flashing](https://github.com/eigatech/zmk-config#dongle-flashing) chapter for instructions.

> [!NOTE]  
> These configurations are meant to be used with builds that are identical to the ones featured in the videos, otherwise they should be used as reference only.

## TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

> [!WARNING]  
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!

## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

Documentation and guides:
- [ZMK Firmware Documentation](https://zmk.dev/docs)
