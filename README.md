## SDL2 Setup

This repository aims to provide a template to initialize a SDL2 project utilizing CMake. This came out of frustration trying to setup SDL within the Jetbrains CLion IDE in macOS.

Within `CMakeLists.txt`, substitute `projectName` with the name of your project.

## macOS Users

Please ensure that you have a recent version of SDL2 from the [SDL2 releases page](https://github.com/libsdl-org/SDL/releases). Make sure that the `SDL2.framework` folder is located either within the `/Libraries/Frameworks` or `~/Libraries/Frameworks` directories.