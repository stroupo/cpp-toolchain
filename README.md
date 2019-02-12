# C++ Toolchain

C++ is a complicated and big language.
Its backwards compatibility on the one hand and modern features on the other hand make it difficult to find a good starting point for writing your own code.
This becomes even worse if we think about additional tools like `CMake` or `git` which clearly optimize the complete process of developing but introduce a tremendous penalty in the learning process because most of these tools cannot be not be added in an intuitive way to the development workflow if one has never used them.
Even for writing simple C++ programs one has to think about a lots of other tools.
We cannot really do something about this.
But we can provide some sort of documentation which outlines the most important tools and how to use them efficiently in your own project without thinking too much about them.

## Operating System
The general discussion is always about Linux vs. Windows vs. MacOS.
In our experience Linux seems to be the best candidate.
With nearly every distribution coding and installing tools can be done without problems.
On Windows developing with tools not developed by Microsoft is a pain in the ass.
We do not have much experience with MacOS.

Choosing a Linux distribution is a matter of taste.
But we recommend one of the following.
- Ubuntu
- Debian
- Arch
- Pop!_OS
- Gentoo for learning skills

### Virtual Machines and Docker
Sometimes it is not feasible to really install a new operating system.
If you already use a certain development environment you do not want to change or if you are working on multiple projects with different needs at once then it may seem appropriate to use an alternative.
For special hardware one could choose an emulator but one should try to work with the given system.
We can use Docker containers or virtual machines (maybe build by Vagrant).

### Shell
- bash
- fish
- ion
- xonsh
- ipython

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

## presentations
### jupyter notebook