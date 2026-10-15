| [Home](index.md) | [Features](features.md) | [Changelog](changelog.md) | [Privacy Policy](privacyPolicy.md) |

## Change Log

All notable changes to the "at89lp-ide" extension will be documented in this file.

### 1.2.1 - 

- **Fix memory report** - Clear when new one is generated.

### 1.2.0 - 2026/10/14

- **Memory report** - Added a memory breakdown tab, to show memory usage.

### 1.1.1 - 2026/09/24

- **Fix deselection of programming and serial ports** - Prevent the UI from deselecting the user selected port when ports are updated.
- **Compilation of multiple source files** - Allow multiple `.c` files to be compiled and not only support header files.

### 1.1.0 - 2026/09/04

- **Remove .gitignore** - remove `.gitignore` from 8051 template.
- **Import Code::Blocks project** - add a command to import Code::Blocks projects into a format AT89LP IDE can build.
- **Export projects to Code::Block projects** - add a command to export projects to a Code::Blocks project format.
- **Improve c_cpp_properties.json generation** - only generate the file when a new project is created or when a Code::Blocks project is imported.
- **Program open hex file** - when no project is open, prompt the user to select a hex file to program.
- **Allow easy addition of include directories** - added a command to allow users to easily add an include directory to the current project.

### 1.0.0 - 2026/08/25

- **Update with valid license** - only update with valid licenses and not invalid ones.
- **Improve GUI** - add labels and placeholders for gui.
- **Update links** - update links to actual product.

### 0.3.11 - 2026/08/25

- **Privacy Policy** - added privacy policy.
- **Improve input validation** - fix UI input validation for programming, building and serial monitor usage.
- **Check open workspace before building/programming** - check whether a workspace is open before trying to build/program.
- **Save walkthrough completion** - prevent the walkthrough from displaying when user already has completed it.

### 0.3.10 - 2026/08/23

- **Bug fixes and improvements** - fix bugs and improve overall code quality.
- **Support custom paths** - allow the user to setup own paths to SDCC and include headers.
- **Build and program process overhaul** - completely overhaul the program and build commands.
- **Fix memory hogging packihx** - fixed improper dependency check for packihx, which caused memory hogging.

### 0.3.9 - 2026/08/23

- **License deactivation** - add a license deactivation command.
- **Rename activation** - rename `Enter License` to `Activate License`.

### 0.3.8 - 2026/08/22

- **Dynamically create .vscode** - create `.vscode/c_cpp_properties.json` when not existing to support existing projects.
- **Open output automatically** - open the output terminal when building and programming.
- **Invalid license bug** - shows invalid license when a license is activated.
- **License system overhaul** - over haul the license validation and activation.
- **Display build output** - display build output, didn't display when build failed

### 0.3.7 - 2026/08/21

- **Update UI to match new VS Code** - smooth UI to match the new VS Code look.
- **Add walkthrough** - to guide a beginner through the setup and usage.
- **Add dependency check** - check regularly if dependencies are installed.

### 0.3.6 - 2026/08/20

- **Error message when no project open** - display error message when no project is open and the user is trying to build.
- **Remove accidental lock** - `programming` could fail to reset causing a lock and preventing the user from flashing.
- **Other small fixes** - User experience improvements.

### 0.3.5 - 2026/08/20

- **Update icon** - change icon.

### 0.3.4 - 2026/08/20

- **SDCC Diagnostics** - Diagnose c files to check for errors lazily.
- **SDCC Preprocessor Keywords** - Updated pre-processor keywords.
- **Prevent license sharing** - Limit license usage to single devices.

### 0.3.3 - 2026/08/18

- **Fixed build bug** - Failed to clean build directory with no error message.
- **Fixed license bug** - Premium activated accidentally.

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