# Puzzle Pegs (C++)

This is the C++ version of the [Puzzle Pegs](https://github.com/Techman/puzzle-pegs) program. It has had a few iterations, from originally using top-level functions to now using a class to represent the entire puzzle.

To view details on the program itself, please visit the main repository linked above.

## Build
CMake is now used as the build system for the project. I did this on purpose to learn more about it. (It is definitely more complicated than needed for a small project like this.)

To build:

1. In the project root, `mkdir build` or otherwise create the `build` directory
2. `cd build` (navigate inside)
3. Run `cmake ..` to run CMake, using the files in the project root.
4. Run `make` (at least on UNIX operating systems)

The compiled binary will be located in the `build/bin` directory.

If you open this project in Visual Studio Code with the CMake Tools extension installed, the extension can automatically configure the project for you. I highly recommend this, as it makes building/debugging/running a one-click experience.
