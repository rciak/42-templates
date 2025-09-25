# 42-templates 🌐
Contains templates that are hopefully useful in doing the Common Core of 42.

## CMake

### How to use Create `compile_commands.json` file for VS-Code

1. Copy `CMakeLists.txt` to a folder like `/github/Ci2-pipex/built`
2. run `cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=ON .`
3. run make with the created Makefile
4. Copy `compile_commands.json` to destination folder like `/github/Ci2-pipex`
