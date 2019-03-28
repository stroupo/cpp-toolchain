# Sublime Text 3: Customization Recommendations

These are recommendations for the configuration of your `Sublime Text 3` editor.
If you want to make things fast you can use an existing one, like [this](https://github.com/lyrahgames/sublime-text-3-config), by following the usage instructions.
As a base requirement you should have fresh installed `Sublime Text 3` on your Linux computer.

## Install Package Control
1. Open `Sublime Text 3`
2. Type `ctrl+shift+p` to open the command palette
3. Type `install` and choose the entry `Install Package Control` 
4. Wait for an answer and close `Sublime Text 3`

## Initialize syncing
- open terminal and `cd` into `~/.config/sublime-text-3/Packages/User`
- init git repository for syncing: `git init` (after packages are installed changes should be committed)
- create repository on GitHub
- add remote to repository `git remote add origin git@github:<username>/sublime-text-3-config.git`
- push all changes to that repo

## Dictionaries for spell checking
- install dictionaries for spell checking:
```
    cd ~/.config/sublime-text-3/Packages
    git clone https://github.com/titoBouzout/Dictionaries.git
```
- turn spell checking on and off by pressing `f6`
- use command pallette with `set language` and choose `Dictionaries: Set Language` to set a new language for spell checking or `Dictionaries: Set Language (Current View)` to set a new language for the current document
- these dictionaries do not belong to the git repo. Therefore they have to be reinstalled every time.

## Shell support
We recommend the following packages for a smooth interaction with the shell.
- Terminal
    + Opens a new system terminal in the current directory or the project directory
- Terminus
    + Opens a shell inside the editor in the current directory

## Git support
Of course, your editor should support the interaction with `git`.
Therefore, we recommend the two following packages.
Make sure `git` is already installed.
- GitSavvy
    + Gives you a smooth and efficient interface to `git` inside your editor
    + Open source
- Sublime Merge
    + It is not a package but an extra program which can be installed by the systems package manager
    + Fast `git`-client
    + Smooth interaction with `Sublime Text 3`

## C++ support
- Clang Format
    + requires `clang-format`
- SublimeLinter
    + using `SublimeLinter-cpplint`, `SublimeLinter-clang` or `SublimeLinter-gcc` is not working properly
- SublimeLinter-contrib-clang-tidy
    + requires `clang-tidy`
- SublimeLinter-cppcheck
    + requires `cppcheck`
- EasyClangComplete
    + requires `clang` and `CMakeLists.txt`

## CMake support
- CMake
- CMakeFormat
    + requires `cmake-format`

## Extra
There are a lots of extra packages out there.
The following packages will make your workflow much more efficient.
- A File Icon
- AdvancedNewFile
- AutoFileName
- Colorsublime
- Dockerfile Syntax Highlighting
- Enki Theme
- Gnuplot
- Hide Menu
- Inc-Dec-Value
- LatexTools
- MarkdownEditing
- MarkdownPreview
- Origami
- Project Manager
- SideBarEnhancements
- Theme - Elementary

## Keybindings and Settings
Please remember to always customize the general settings and key bindings.
Choose the key bindings you can remember easily and use efficiently.
Look [here](https://github.com/lyrahgames/sublime-text-3-config) if you need some ideas.