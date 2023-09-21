# 6800 NOP tester

Hardware and firmware for creating a simple Motorola MC6800 CPU NOP tester.

## Directory Outline

- [`~/hardware/`](hardware) is for Fusion 360 design files.
- [`~/firmware/`](firmware) is for firmware souce code and binaries.
- [`~/mechanical/`](mechanical) is for mechanical CAD design files for the encloser or box. Create seperate directories for `.stl` or other files for 3D printing for easy accesss.

## Fusion 360 Libraries

Besides the default libraries provided with Fusion 360, we also include the libraries provided by others (as a submodule), as well as our own libraries wuith tailored symbols and footprints.
To use these libraries after cloning the repository, run the following commands:

```bash
git submodule init
git submodule update
```

> To add another repository as submodule, use the command `git submodule add <URL_OF_REPOSITORY>`.
