This repository contains the settings for JetBrains products that I share between multiple machines, 
such as keymaps, font sizes, plugins, and more.

### Keymap

The current JetBrains keymap for macOS is located at [inchestnov-macos.xml](./keymaps/inchestnov-macos.xml).

JetBrains stores keymap files in the following directory: `~/Library/Application Support/JetBrains/ProductName/keymaps/`. 
To use the provided keymap, navigate to this directory and run the following command:

```bash
curl https://raw.githubusercontent.com/inchestnov/jetbrains/master/keymaps/inchestnov-macos.xml > inchestnov-macos.xml
```

### Templates

Personal templates, like `fixme` or `todo`, are located at [templates](./templates/).

To use it, navigate to `~/Library/Application Support/JetBrains/ProductName/templates/` and do:

```bash
curl https://raw.githubusercontent.com/inchestnov/jetbrains/master/templates/personal.xml > personal.xml && \\
curl https://raw.githubusercontent.com/inchestnov/jetbrains/master/templates/personal-go.xml > personal-go.xml
```
