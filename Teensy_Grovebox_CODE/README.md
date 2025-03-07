# Teensy Grovebox Code
## Overview
- This project uses the PlatformIO development tool.
- The entry point for the program is in `src/main.cpp`
## Dependencies
### Dependencies handled by PlatformIO
- [IoAbstraction](https://github.com/davetcc/IoAbstraction)
    - This library makes it easier to use IO expander pins and Teensy pins together.
- [TaskManagerIO](https://github.com/davetcc/TaskManagerIO)
    - We use this library for scheduling and task management.
### Dependencies in the `lib` folder
- [LVGL - Light and Versatile Embedded Graphics Library](https://lvgl.io/)
    - All GUIs in the project are created with LVGL.
- [ILI9341_T4](https://github.com/vindar/ILI9341_T4)
    - A optimized display driver for the ILI9341 TFT LCD + Teensy4 combo.
## Setup and Build
- Install the PlatformIO extension in Visual Studio Code.
- Open the `Teensy_Grovebox_CODE` folder with Visual Studio Code.
- All the required tools and libraries should be downloaded automatically.
- You can now start to build and program your Teensy.
- > The Arduino VSCode extension may conflict with PlatformIO. You can disable it in your workspace.
## Folders
- `src`
    - All the source files for the project.
    - Each subfolder has related code files.
- `lib`
    - External libraries that are not managed by PlatformIO are here.
- `gui-audio_tool`
    - This is copied from the GUI tool of the  [Teensy Audio Library](https://github.com/PaulStoffregen/Audio)
    - Some custom audio objects for this project are added to the tool.
## Code Structure
(TBD)
