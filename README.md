# 42-templates 🌐

Contains templates that are hopefully useful in doing the Common Core of 42.

## CMake

### How to use Create `compile_commands.json` file for VS-Code

1. Copy `CMakeLists.txt` to a folder like `/github/Ci2-pipex/build` and adopt
   the copy.
2. run `cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=ON .` there
3. run make with the created Makefile
4. Copy the created `compile_commands.json`
   to the destination folder like `/github/Ci2-pipex`
