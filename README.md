# OneMsTaskTimer Library

[![Arduino Compile Sketches](https://github.com/Andy4495/OneMsTaskTimer/actions/workflows/arduino-compile-sketches.yml/badge.svg)](https://github.com/Andy4495/OneMsTaskTimer/actions/workflows/arduino-compile-sketches.yml)
[![Check Markdown Links](https://github.com/Andy4495/OneMsTaskTimer/actions/workflows/CheckMarkdownLinks.yml/badge.svg)](https://github.com/Andy4495/OneMsTaskTimer/actions/workflows/CheckMarkdownLinks.yml)

This is a copy of the [OneMsTaskTimer library][4] that is included with the [Energia application][1].

Texas Instruments MSP430 and Tiva microcontrollers can be compiled using the Arduino IDE/CLI by installing the relevant [platform cores][6] through the Boards Manager. However, the OneMsTaskTimer library is included in the Energia application itself, and not the specific platform core. This means that if you install the MSP430 or Tiva core, you don't end up getting the OneMsTaskTimer library. So a sketch that used that library and compiled fine on Energia would not compile on Arduino without some additional steps.

So I am publishing this library separately so that it can be easily installed as a library for the Arduino IDE or CLI. This also makes it available for use in GitHub workflow actions.

## Usage

See the sketches in the `examples` folder.

## License

The library source code (OneMsTaskTimer.cpp and OneMsTaskTimer.h) is licensed under the terms of the GNU [Lesser General Public License][100] as published by the Free Software Foundation; either [version 2.1][102] of the License, or (at your option) any later version.

The example sketches (OneMsTaskTimerBlink.ino and OneMsTaskTimerBlink_1ms.ino) are in the public domain.

[1]: https://energia.nu
[4]: https://github.com/robertinant/EnergiaNG/tree/master/libraries/OneMsTaskTimer
[6]: https://github.com/Andy4495/TI_Platform_Cores_For_Arduino
[100]: https://www.gnu.org/licenses/licenses.html#LGPL
[102]: https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html
[//]: # ([200]: https://github.com/Andy4495/OneMsTaskTimer)

[//]: # (This is a way to hack a comment in Markdown. This will not be displayed when rendered.)
