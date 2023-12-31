# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## Requirements:
- [Basic requirements](https://www.lazyvim.org/#%EF%B8%8F-requirements)
- Optional: [compiledb](https://github.com/nickdiego/compiledb) (tool for generating Clang's JSON Compilation Database file for GNU make-based build systems)

## Usage:

Small adaption from the standard lazyvim installation guide (https://www.lazyvim.org/installation):
- Required
```
 mv ~/.config/nvim ~/.config/nvim.bak  
```
- Optional but recommended
```
mv ~/.local/share/nvim ~/.local/share/nvim.bak
mv ~/.local/state/nvim ~/.local/state/nvim.bak
mv ~/.cache/nvim ~/.cache/nvim.bak  
```
- Clone this repo
```
git clone https://github.com/leCoq42/LazyVim-config.git ~/.config/nvim  
```
- Remove the .git folder, so you can add it to your own repo later
```
rm -rf ~/.config/nvim/.git  
```
- Start Neovim!
```
nvim  
```
## Tips:
- For macOS users: For the option key (⌥) to work as <M> you may need to adjust some settings:
    - iTerm2: Select Esc+ as the Option key setting in Preferences -> Profiles -> Keys.
