# C++ Toolchain

C++ is a complicated and big language.
Its backwards compatibility on the one hand and modern features on the other hand make it difficult to find a good starting point for writing your own code.
This becomes even worse if we think about additional tools like `CMake` or `git` which clearly optimize the complete process of developing but introduce a tremendous penalty in the learning process because most of these tools cannot be not be added in an intuitive way to the development workflow if one has never used them.
Even for writing simple C++ programs one has to think about a lots of other tools.
We cannot really do something about this.
But we can provide some sort of documentation which outlines the most important tools and how to use them efficiently in your own project without thinking too much about them.

## Operating System

**Recommendation:** Use a Linux distribution.

**Explanation:**
The operating system is the most basic part of the development environment and is used in every single stage of a software project.
Hence, it should support the development workflow in such a way that the programmer should not realize its existence.
Therefore an ideal operating system for development would fulfill the following conditions.

- lightweight (older hardware should be capable of running this system)
- optimized for the hardware it is used on
- fast installation to new hardware
- fast booting and shutdown
- short response times (user should not wait)
- efficient interaction and communication with user (for example via a terminal through keyboard)
- capable of graphical output (humans are more attracted to nice looking designs)
- fast internet browsing for research
- fast installation of new packages and tools from modern repositories
- easily upgradeable without being forced to
- good defaults so no real configuration is needed
- compatibility to all development tools
- easy to learn for newcomers
- open source system / providing ways to use open source software
- free to use

In reality there is no operating system which fulfills all these conditions.
As a consequence we look for the best subset.
In our experience any Linux distribution seems to be a really good candidate.
Most Linux distributions are lightweight, easy to install, fast to boot and shutdown and free to use.
With nearly every distribution coding and installing tools can be done without problems.
Upgrading a Linux distribution can be done manually.
Choosing a specific Linux distribution is a matter of taste.
But we recommend one of the following.
- Ubuntu
- Arch
- Pop!_OS

### Shell
- bash
- fish
- ion
- xonsh

- trans-shell

## Text Editor
### Sublime Text
#### Packages
### Atom
### Others

## C++ Compiler
### Language standard
### GCC
### Clang
### Intel

## Libraries
### Boost
### fmt
### Eigen
### Qt
### OpenGL
### Intel MKL
### OpenMP
### MPI, thrill, ...

## CUDA
### Thrust

## Build System
### CMake
### Meson
### Others

## Version Control Systems
### Git
#### Initialization
user name and mail
core editor
standard hooks
#### Hooks
#### Workflow - Gitflow

## Git Server
### Github
#### Users and Repos
#### Organizations
#### Issues
#### Projects
#### Wikis

## C++ Package Manager

## Code Utilities
### clang-format
### clang-tidy
### cmake-format
### good-commit-message-hook

## Docker
### DockerHub

## Unit Testing Frameworks
### doctest
### Catch

## Mocking Frameworks
### trompeloeil

## Test-driven Development

## Microbenchmarking
### Google
### Nonius etc...

## Debugging
### GDB
### Valgrind

## Documentation
### ReadTheDocs

## Continuous Integration
### Docker
### CircleCI
### Code Coverage
#### kcov
#### gcov

## Continuous Deployment
### Docker
### Releases

## Project Workflow from Scratch
### Starting a new project
How to iteratively include all important tools without loosing overview?
Project Template?
Multiple Project Templates?
Starting from Scratch?
One-person-project vs small-group-project vs big-group-project vs what-the-hell-projects?
### Working on existing projects
### Virtual Machines and Docker
Sometimes it is not feasible to really install a new operating system.
If you already use a certain development environment you do not want to change or if you are working on multiple projects with different needs at once then it may seem appropriate to use an alternative.
For special hardware one could choose an emulator but one should try to work with the given system.
We can use Docker containers or virtual machines (maybe build by Vagrant).

## presentations
### jupyter notebook