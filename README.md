# Source Code Pro font for Android

![License badge](https://img.shields.io/badge/License-MIT-blue) ![Magisk requisition](https://img.shields.io/badge/Magisk-19%2B-brightgreen)

## Introduction

[Source Code Pro](https://fonts.adobe.com/fonts/source-code-pro) is a `monospaced` font family for user interface and coding environments. Its simplicity and clearness always attract people to love and enjoy it. There are a lot of people like me who prefer the font in editors, IDEs, and browsers. So why not try it out on Android? This module just help you do that with the art of Magisk: **keep the system actually untouched.**

## Details about this module

- Font file are renamed from with Adobe's latest release(`Roman 1.010 variable`).
- For monospaced font, Android only support one font weight and one font style:
  ![monospaced font config in fonts.xml](./md-assets/monospaced-font-config.png)
  Considering the compatibility and to make least trouble when user wants to migrate to other fonts, I give up the idea to install a modified `fonts.xml`.
- Should not conflict with other font packs. (There's now no font packs which replace the total `/system/fonts` directory I guess.)

## Installation Guide

- Using the lastest Magisk release is recommended.
- Download, flash, then reboot to enjoy it!

## Preview

![Chrome](./md-assets/Screenshot_Chrome_20190814-114107.png)

![Magisk](./md-assets/Screenshot_Magisk_Manager_20190814-114124.png)

![Termux](./md-assets/Screenshot_Termux_20190814-114413.png)

## Changelog

- Aug 14, 2019 - v1.0  (Font version 1.010, Roman Variable)

## License

- Adobe Source Code License [SIL Open Font License 1.1
  ](https://github.com/adobe-fonts/source-code-pro/blob/release/LICENSE.txt)

- [MIT](https://github.com/moposx/Magisk-source-code-pro/blob/master/LICENSE) License for this module

## Credits

- Adobe Fonts
- Magisk Project

## Feedback and Support

- Create an issue in the [github repository](https://github.com/moposx/Magisk-source-code-pro)
- [Email me](mailto:moposx01@gmail.com)
