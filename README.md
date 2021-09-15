# Pico

## Debugging the Pico in C++ Boilerplate Project

settings.json

Add the following lines of code to your settings.json file which you can access by using the ctrl+, shortcut and clicking the open JSON file button in the top right corner of the VSCode window. Alter the “PATH TO openocd.exe” to wherever your openocd is, including the openocd command for example: "Users/nechry/pico/openocd/openocd".

launch.json

As above, replace the "PATH TO X" with the actual path to X. And the location of the elf file to the actual path of the ELF file.

CMakeLists.txt

Edit [CMakeLists.txt](CMakeLists.txt) and follow the instructions, you should make sure you:

edit your project name
include the libraries you need
link the libraries to your project
