# ARCHIVED - 22/07/25
Migrated to [Codeberg](https://codeberg.org/stikypiston/rofi-ultimenu), go check it out!

# rofi-ultimenu
A Rofi configuration, combining useful modi into a single view

## Setup
To set up the **Ultimenu**, first clone the git repo:  

```bash
git clone https://github.com/StikyPiston/rofi-ultimenu
```

Then, copy the `ultimenu.rasi` file into your `~/.config/rofi/` folder.

Inside your own `config.rasi` file, add the line: `@import "ultimenu"`, and remove the "configuration" section of your own config.

To use **Ultimenu**, just run `rofi -show combi`, or bind that command to a keybind in your Window Manager, for example using SXHKD could look like:

```bash
super + grave
	rofi -show combi
```

---
