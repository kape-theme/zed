# ☕ Kape for Zed

Kape is a warm, dark color scheme for **Zed** code editor, rooted in coffee, earth, and amber tones.

## Installation

### Option 1: Manual Installation

1. Create the Zed themes directory:
   ```bash
   mkdir -p ~/.config/zed/themes
   ```

2. Copy the theme file:
   ```bash
   cp kape.json ~/.config/zed/themes/
   ```

3. Configure Zed to use the theme:
   - Open Zed
   - Open settings with `Ctrl+,` (or `Cmd+,` on macOS)
   - Add or update the theme settings:
     ```json
     {
       "theme": {
         "dark": "Kape",
         "light": "Kape"
       }
     }
     ```

4. Close and reopen Zed (or reload the window) for changes to take effect

### Option 2: Using the UI

1. Open Zed
2. Open settings with `Ctrl+,` (or `Cmd+,` on macOS)
3. In the settings panel, search for "theme"
4. Select "Kape" from the available themes dropdown

### Option 3: Using Git (Recommended for Updates)

1. Navigate to your Zed themes directory:
   ```bash
   cd ~/.config/zed/themes
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/kape-theme/zed.git
   ```

3. Add to your Zed settings:
   ```json
   {
     "theme": {
       "dark": "Kape"
     }
   }
   ```

4. To update in the future:
   ```bash
   cd ~/.config/zed/themes/kape-zed
   git pull
   ```

## Color Palette

| Element | Hex |
|---------|-----|
| Background | `#181616` |
| Surface | `#1e1b1b` |
| Text | `#d4be98` |
| Muted Text | `#928374` |
| Keywords | `#7b8fd4` |
| Functions | `#b06880` |
| Strings | `#b4c76e` |
| Numbers | `#e7bb5c` |
| Types | `#689d8a` |
| Comments | `#928374` |

See the main [Kape repository](https://github.com/kape-theme/kape) for the complete palette with RGB and HSL values.

## Features

- **Syntax Highlighting**: Carefully crafted colors for all syntax elements
- **UI Elements**: Consistent coloring for buttons, selections, and hover states
- **Terminal Colors**: Includes ANSI color mapping for integrated terminal
- **Diff Colors**: Specific colors for git diff visualization
- **Dark Theme Optimized**: Designed for comfortable long-hour coding sessions

## Customization

To customize the theme, edit `~/.config/zed/themes/kape.json`. The file contains:

- **accents**: Main color palette
- **style**: UI component colors and text colors
- **syntax**: Syntax highlighting rules
- **terminal**: Terminal color mappings

After editing, reload Zed or restart the window.

## Troubleshooting

- **Theme not loading**: Check that the filename is exactly `kape.json`
- **Changes not applying**: Reload the Zed window (`Ctrl+Shift+P` → "Reload Window")
- **Theme not in list**: Make sure the file is in `~/.config/zed/themes/` 

## Platform-Specific Paths

- **Linux**: `~/.config/zed/themes/`
- **macOS**: `~/.config/zed/themes/`
- **Windows**: `%APPDATA%\Zed\themes\`

## Credits

Special thanks to [meaayu](https://github.com/meaayu) for the initial implementation of this port.

## Contributing

Found an issue or have a suggestion? Open an issue or PR on the [main Kape repository](https://github.com/kape-theme/kape).

## License

MIT © gabiuz
