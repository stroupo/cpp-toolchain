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
- Inc-Dec-Value
- LatexTools
- MarkdownEditing
- MarkdownPreview
- Origami
- Theme - Elementary

## Keybindings
### Toggle Comments
    { "keys": ["ctrl+7"], "command": "toggle_comment", "args": { "block": false } },
    { "keys": ["ctrl+shift+7"], "command": "toggle_comment", "args": { "block": true } },
### Pasting and Indentation
    { "keys": ["ctrl+v"], "command": "paste_and_indent" },
    { "keys": ["ctrl+shift+v"], "command": "paste" },
    { "keys": ["ctrl+shift+r"],  "command": "reindent" },
### Standard Overlays
    { "keys": ["alt+f"], "command": "show_overlay", "args": {"overlay": "goto", "show_files": true} },
    { "keys": ["alt+n"], "command": "show_overlay", "args": {"overlay": "command_palette"} },
    { "keys": ["alt+b"], "command": "prompt_select_workspace" },
    { "keys": ["ctrl+r"], "command": "show_overlay", "args": {"overlay": "goto", "text": "@"} },
    { "keys": ["ctrl+g"], "command": "show_overlay", "args": {"overlay": "goto", "text": ":"} },
    { "keys": ["ctrl+,"], "command": "show_overlay", "args": {"overlay": "goto", "text": "#"} },
### AdvancedNewFile
    { "keys": ["ctrl+alt+n"], "command": "advanced_new_file_new"},
    { "keys": ["ctrl+alt+m"], "command": "advanced_new_file_move"},
    { "keys": ["ctrl+alt+r"], "command": "advanced_new_file_delete"},
### Origami
    { "keys": ["alt+k", "up"], "command": "travel_to_pane", "args": {"direction": "up"} },
    { "keys": ["alt+k", "right"], "command": "travel_to_pane", "args": {"direction": "right"} },
    { "keys": ["alt+k", "down"], "command": "travel_to_pane", "args": {"direction": "down"} },
    { "keys": ["alt+k", "left"], "command": "travel_to_pane", "args": {"direction": "left"} },
    { "keys": ["alt+k", "shift+up"], "command": "carry_file_to_pane", "args": {"direction": "up"} },
    { "keys": ["alt+k", "shift+right"], "command": "carry_file_to_pane", "args": {"direction": "right"} },
    { "keys": ["alt+k", "shift+down"], "command": "carry_file_to_pane", "args": {"direction": "down"} },
    { "keys": ["alt+k", "shift+left"], "command": "carry_file_to_pane", "args": {"direction": "left"} },
    { "keys": ["alt+k", "ctrl+up"], "command": "create_pane", "args": {"direction": "up"} },
    { "keys": ["alt+k", "ctrl+right"], "command": "create_pane", "args": {"direction": "right"} },
    { "keys": ["alt+k", "ctrl+down"], "command": "create_pane", "args": {"direction": "down"} },
    { "keys": ["alt+k", "ctrl+left"], "command": "create_pane", "args": {"direction": "left"} },
    { "keys": ["alt+k", "ctrl+shift+up"], "command": "destroy_pane", "args": {"direction": "up"} },
    { "keys": ["alt+k", "ctrl+shift+right"], "command": "destroy_pane", "args": {"direction": "right"} },
    { "keys": ["alt+k", "ctrl+shift+down"], "command": "destroy_pane", "args": {"direction": "down"} },
    { "keys": ["alt+k", "ctrl+shift+left"], "command": "destroy_pane", "args": {"direction": "left"} },
    { "keys": ["alt+k", "ctrl+z"], "command": "zoom_pane", "args": {"fraction": 0.9} },
    { "keys": ["alt+k", "ctrl+shift+z"], "command": "unzoom_pane", "args": {} },
    { "keys": ["alt+k", "ctrl+c"], "command": "resize_pane", "args": {"orientation": "cols"} },
    { "keys": ["alt+k", "ctrl+r"], "command": "resize_pane", "args": {"orientation": "rows"} },
### Inc-Dec-Value
    { "keys": ["alt+up"], "command": "inc_dec_value", "args": {"action": "inc_min"} },
    { "keys": ["alt+down"], "command": "inc_dec_value", "args": {"action": "dec_min"} },
### Terminus
    { "keys": ["alt+r"], "command": "toggle_terminus_panel" },
    { "keys": ["alt+g"], "command": "terminus_open", "args": {"config_name": "Default", "cwd": "${file_path:${folder}}"}},


## Settings