| [Home](index.md) | [Features](features.md) | [Changelog](changelog.md) | [Privacy Policy](privacyPolicy.md) |

- [Features](#features)
  - [Build Menu](#build-menu)
  - [Program Menu](#program-menu)
  - [Serial Monitor](#serial-monitor)
- [Commands](#commands)
  - [Programmer's Calculator](#programmers-calculator)
    - [Examples](#examples)
  - [Import Code::Blocks Project](#import-codeblocks-project)
  - [Export to Code::Blocks Project](#export-to-codeblocks-project)
  - [Add include directory](#add-include-directory)


## Features

### Build Menu
![Build Menu](assets/build_menu.png)

Compile your 8051 projects using this simple integrated build menu. Designed specifically so that you do not have to struggle to change any of your project settings. Beginner friendly but gives you all the power you need. Use the memory report to know exactly how much space you have to work with!

### Program Menu
![Program Menu](assets/program_menu.png)

Program/Flash your AT89LP devices with a powerful built-in programmer. Easily change your targeted device, serial port and Baud rate with the dropdown menus.

### Serial Monitor
![Serial Monitor Menu](assets/serial_monitor_menu.png)

Debug your serial communications directly inside VS Code using the built-in serial monitor. Choose your serial port and baud rate with ease. Send and receive serial data using the integrated serial monitor, without installing any external dependencies.

## Commands

Run all of the following commands from the VS Code command prompt. Open the command prompt using `F1` or `Ctrl + Shift + P`.
Then type the command you'd like to run and press enter to run it. Example:
> AT89LP: Programmer's Calculator.

### Programmer's Calculator

Use this calculator to calculate mathematical expression in any base.

| Base        | Format | Example |
| ----------- | ------ | ------- |
| Decimal     | -      | `32`    |
| Hexadecimal | `0x`   | `0x34`  |
| Binary      | `0b`   | `0b10`  |
| Octadecimal | `0o`   | `0o24`  |

Type any expression in the input box and press `Enter` to calculate.

#### Examples

- > 0b01 + 0b10
- > 0b1011 ^ 0b0100
- > 0b1001 & 0b1111
- > 0x34 + 2321 - 0b00101110 * 0o54 / 64

### Import Code::Blocks Project

Allows the user to import an existing Code::Blocks project in a format which the AT89LP IDE can understand.

- Start by creating a blank project using the `AT89LP: Create project` command.
- Open the empty project in VS Code.
- Run the `Import Code::Blocks Project` command.
- Select the Code::Blocks project file (`.cbp`) when prompted.

### Export to Code::Blocks Project

Easily export a project to a Code::Blocks compatible project.

- Run the `Export as Code::Blocks Project` command.
- Select a destination to where you want to export to.
- Name your export when prompted.

### Add include directory

Add the directories you want to include in your build. The header files in this directory will be added to the build.
Useful for when you have a header like `REG51ATLPRB2.h`, which is always included.

- Run the `Add include directory` command.
- Select the directory you want to include when prompted.

---

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JodusMelodus)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@JodusMelodus)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/jodusmelodus_dev/)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)](https://marketplace.visualstudio.com/publishers/jodusmelodus-dev)
[![Email](https://img.shields.io/badge/Email-philipgricius+jodusmelodus%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:philipgricius+jodusmelodus@gmail.com)

---

**© 2026 Philip. All rights reserved.**

AT89LP is proprietary software. The free version is available through the
Visual Studio Code Marketplace. Premium features are available separately.

AT89LP is an independent project and is not affiliated with or endorsed by
Microsoft Corporation or Microchip Technology Inc.