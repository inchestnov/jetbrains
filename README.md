This repository contains the settings for JetBrains products that I share between multiple machines, 
such as keymaps, font sizes, plugins, and more.

### Usage

Just clone repository and create symlinks

```bash
git clone https://github.com/inchestnov/jetbrains.git
cd jetbrains
```

#### Keymap

The current JetBrains keymap for macOS is located at [inchestnov-macos.xml](./keymaps/inchestnov-macos.xml).

JetBrains stores keymap files in the following directory: `~/Library/Application Support/JetBrains/ProductName/keymaps/`. 
To use the provided keymap, create symlink using the following command:

```bash
ln -s $(pwd)/keymaps/inchestnov-macos.xml ~/Library/Application\ Support/JetBrains/ProductName/keymaps/inchestnov-macos.xml
```

#### Templates

Personal templates, like `fixme` or `todo`, are located at [templates](./templates/).

To use it, navigate to `~/Library/Application Support/JetBrains/ProductName/templates/` and do:

```bash
ln -s $(pwd)/templates/personal.xml ~/Library/Application\ Support/JetBrains/ProductName/templates/personal.xml
ln -s $(pwd)/templates/personal-go.xml ~/Library/Application\ Support/JetBrains/ProductName/templates/personal-go.xml
```
