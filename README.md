# ZMK Config for Lak 
ZMK keyboard firmware shield for [Lak](https://github.com/BrokenFlows/Lak)

![Lak Photo]f(https://github.com/BrokenFlows/Lak/blob/master/images/lak.jpegf)

## What is zmk-lak?
This repository defines and builds [ZMK keyboard firmware](https://zmk.dev) for the Lak keyboard shield with [nice!nano](https://nicekeyboards.com/nice-nano) V1 and V2.

## How do I use this firmware?
Ready-to-flash firmware files for nice!nanos can be downloaded from the latest build on the GitHub "[Actions](https://github.com/BrokenFlows/zmk-lak/actions)" tab above.
To flash the firmware onto your nice!nano, follow the [Flashing, Firmware, and Bootloaders section of the nice!nano docs](https://nicekeyboards.com/docs/nice-nano/getting-started/#flashing-firmware-and-bootloaders).

The default keymap is a simple QWERTY keymap, which is useful for verifying the wiring of the keyboard.
To customise the keymap to your liking, [fork this repo](https://github.com/BrokenFlows/zmk-lak/fork) and modify [`config/lak.keymap`](https://github.com/BrokenFlows/zmk-lak/blob/master/config/lak.keymap) in your repo.
When you commit and push your changes, GitHub will then build your ready-to-flash firmware in the GitHub "Actions" tab of your own repo.

Please refer to the [ZMK docs](https://zmk.dev/docs/) if necessary (the [troubleshooting section](https://zmk.dev/docs/troubleshooting/#dtlibdterror) can be particularly helpful).

