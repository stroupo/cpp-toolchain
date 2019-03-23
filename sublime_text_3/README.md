# Sublime Text 3: Customization Recommendations

## Install Package Control

- open `Sublime Text 3`
- install package control:
    + `ctrl+shift+p` to open command pallette
    + type `install` and choose entry `Install Package Control` 
- close `Sublime Text 3`

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

- Terminal
- Terminus

## Git support
- GitSavvy
    + requires `git`
- Sublime Merge
    + is not a package but an extra program

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

- A File Icon
- AdvancedNewFile
- Auto Hide sidebar
- AutoFileName
- Colorsublime
- Dockerfile Syntax Highlighting
- Enki Theme
- Gnuplot
- Inc-dec-value
- LatexTools
- MarkdownEditing
- MarkdownPreview
- Origami
- Theme - Elementary

## Keybindings
## Settings