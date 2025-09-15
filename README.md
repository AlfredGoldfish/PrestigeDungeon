# Prestige Dungeon

This repository contains a scaffold of a C++/SFML 2D prestige dungeon RPG. The goal of this scaffold is to provide a clean and organised file layout, allowing you to understand and implement the various systems of the game incrementally. No working game code is provided yet; instead, each class is represented by a pair of header and source files containing empty stubs and descriptive comments.

## Project Purpose & Rationale

The structure in this repository is designed to help orient developers and learners to the overall architecture of a 2D RPG built with SFML. By laying out each core engine component, game system, entity, manager, state, data module, UI element and tool, you can plan and track work items without the distraction of implementation details. Each file includes a "book‑intro" comment describing its purpose, responsibilities and collaborators.

## How to Use

* Explore the `src/` directory to see the breakdown of different modules.
* Each class has a corresponding `.h` and `.cpp` file. Start by reading the comments in the header file to understand what the class is intended to do.
* Implement functionality module by module, keeping includes limited to your own header until cross‑wiring is required.
* This repository does not contain a `main()` entry point or a build system. You can add CMake or other build scripts once you begin implementation.

## Optional Files

Stub versions of `CMakeLists.txt`, `.editorconfig`, `.clang-format` and `LICENSE` are included and may be customised as development progresses.

