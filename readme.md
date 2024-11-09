## Original Firmware Source

The original VIAL QMK firmware for the Keychron V1 ISO keyboard can be found [here](https://github.com/vial-kb/vial-qmk/keyboards/keychron/v1).

## Changes from Original Firmware

-   **Caps Lock Indicator Color:** Changed caps lock indicator color to red for better visibility.
-   **Layer Activation Highlight:** When switching to any layer greater than 0, the keys bound to an action will be highlighted.
-   **Windows Layer Removal:** The Windows layer has been removed for users who don't use Windows.
-   **Caps Word Mode:** Press Left Shift + Right Shift to enable Caps Word mode for enhanced functionality.
-   **Wide Text Mode:** Added a wide text mode for versatile text manipulation.
-   **TaUnt TeXt MoDe:** Added a fun and playful text mode for a unique typing experience.
-   **Key Lock Mode:** Key Lock mode is added, though not configured in VIA yet.

## VIAL Keymap

The VIA keymap includes various features on layer 1, such as media keys and volume control.

### Installation

1. Make sure

- dfu-util
- gcc-arm-embedded
- qmk

are installed.

2. Put your keyboard into DFU mode.
3. Run `make keychron/v1/iso_encoder:frostplexx:flash`


# Quantum Mechanical Keyboard Firmware

[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/qmk)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the Clueboard product line.

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [VitePress](https://vitepress.dev/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls).

## Supported Keyboards

* [Planck](/keyboards/planck/)
* [Preonic](/keyboards/preonic/)
* [ErgoDox EZ](/keyboards/ergodox_ez/)
* [Clueboard](/keyboards/clueboard/)
* [Cluepad](/keyboards/clueboard/17/)
* [Atreus](/keyboards/atreus/)

The project also includes community support for [lots of other keyboards](/keyboards/).

## Maintainers

QMK is developed and maintained by Jack Humbert of OLKB with contributions from the community, and of course, [Hasu](https://github.com/tmk). The OLKB product firmwares are maintained by [Jack Humbert](https://github.com/jackhumbert), the Ergodox EZ by [ZSA Technology Labs](https://github.com/zsa), the Clueboard by [Zach White](https://github.com/skullydazed), and the Atreus by [Phil Hagelberg](https://github.com/technomancy).

## Official Website

[qmk.fm](https://qmk.fm) is the official website of QMK, where you can find links to this page, the documentation, and the keyboards supported by QMK.
