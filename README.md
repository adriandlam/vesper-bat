# Vesper for bat & Sublime Text

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Peppermint and orange flavored dark theme for [bat](https://github.com/sharkdp/bat) and any TextMate-compatible app. Port of the [Vesper](https://github.com/raunofreiberg/vesper) VS Code theme by [Rauno Freiberg](https://github.com/raunofreiberg).

## Color Palette

| Role               | Color     | Hex       |
| ------------------- | --------- | --------- |
| Background          | ![#101010](https://via.placeholder.com/12/101010/101010.png) | `#101010` |
| Foreground          | ![#CCCCCC](https://via.placeholder.com/12/CCCCCC/CCCCCC.png) | `#CCCCCC` |
| Strings             | ![#99FFE4](https://via.placeholder.com/12/99FFE4/99FFE4.png) | `#99FFE4` |
| Keywords / Constants | ![#FFC799](https://via.placeholder.com/12/FFC799/FFC799.png) | `#FFC799` |
| Comments            | ![#7D7D7D](https://via.placeholder.com/12/7D7D7D/7D7D7D.png) | `#7D7D7D` |
| Errors              | ![#FF8080](https://via.placeholder.com/12/FF8080/FF8080.png) | `#FF8080` |
| Operators           | ![#65737E](https://via.placeholder.com/12/65737E/65737E.png) | `#65737E` |
| Functions           | ![#FFFFFF](https://via.placeholder.com/12/FFFFFF/FFFFFF.png) | `#FFFFFF` |

## Installation

### bat

1. Copy the theme file to bat's theme directory:

   ```sh
   cp Vesper.tmTheme "$(bat --config-dir)/themes/"
   ```

2. Rebuild the bat cache:

   ```sh
   bat cache --build
   ```

3. Use the theme:

   ```sh
   bat --theme=Vesper file.txt
   ```

   Or add it to your bat config file (`bat --config-file`):

   ```
   --theme="Vesper"
   ```

### Sublime Text

1. Copy `Vesper.tmTheme` to your Sublime Text Packages/User directory:
   - **macOS:** `~/Library/Application Support/Sublime Text/Packages/User/`
   - **Linux:** `~/.config/sublime-text/Packages/User/`
   - **Windows:** `%APPDATA%\Sublime Text\Packages\User\`

2. Select the theme via **Preferences > Color Scheme > Vesper**.

## Credits

Based on the [Vesper](https://github.com/raunofreiberg/vesper) VS Code theme by [Rauno Freiberg](https://github.com/raunofreiberg).

## License

[MIT](LICENSE)
