The editor follows your operating-system theme by default and stores preferences outside the application directory. Game-version preferences are remembered per installation.

## Theme

Use **Auto theme**, **Light** or **Dark** in the application toolbar. Auto follows the operating-system setting. The manual's theme button is separate and cycles through system, light and dark.

## User-data locations

| Operating system | Default application directory |
| --- | --- |
| Windows | `%AppData%\eu5-population-editor` |
| GNU/Linux | `~/.config/eu5-population-editor` |

The application stores preferences, remembered game versions and its map cache here. On Linux, a custom XDG configuration directory can change the base location. Saved projects use the locations you choose in Save As.

Your `.eu5popproj` files and exported mods are stored in the locations you explicitly choose. Back them up separately. Close the application before manually moving or removing its settings/cache directory.

## Supported game version

Open **Export Mod** to change **Supported EU5 version** and choose **Save game version**. The first default is `1.4.5`. The value is saved for that installation even if you do not export.

Loading the installation root or its `game` subdirectory refers to the same saved installation setting. Update the field when appropriate, but use migration whenever the actual source data has changed.

## Application shortcuts

| Shortcut | Action |
| --- | --- |
| `Ctrl+S` | Save confirmed Working changes |
| `Ctrl+Shift+S` | Save As |
| `Ctrl+O` | Open a project |
| Arrow keys while the map is focused | Pan the map |

Resolve pending drafts before undoing or redoing confirmed changes. The toolbar shows whether actions are available for the current state.

## Manual shortcuts

Press `/` or `Ctrl+K` to open manual search. Use the arrow keys to move through results, Enter to follow a result and Escape to close the dialog. Search runs locally in your browser, including when the built manual is opened from disk.
