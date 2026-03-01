# Vesper for bat & Sublime Text

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Peppermint and orange flavored dark theme for [bat](https://github.com/sharkdp/bat) and any TextMate-compatible app. Port of the [Vesper](https://github.com/raunofreiberg/vesper) VS Code theme by [Rauno Freiberg](https://github.com/raunofreiberg).

![Preview](preview.png)

### As fzf preview

![fzf Preview](preview-fzf.png)

## Color Palette

| Role               | Color     | Hex       |
| ------------------- | --------- | --------- |
| Background          | ![](https://img.shields.io/badge/%20-101010?style=flat-square&color=101010) | `#101010` |
| Foreground          | ![](https://img.shields.io/badge/%20-CCCCCC?style=flat-square&color=CCCCCC) | `#CCCCCC` |
| Strings             | ![](https://img.shields.io/badge/%20-99FFE4?style=flat-square&color=99FFE4) | `#99FFE4` |
| Keywords / Constants | ![](https://img.shields.io/badge/%20-FFC799?style=flat-square&color=FFC799) | `#FFC799` |
| Comments            | ![](https://img.shields.io/badge/%20-7D7D7D?style=flat-square&color=7D7D7D) | `#7D7D7D` |
| Errors              | ![](https://img.shields.io/badge/%20-FF8080?style=flat-square&color=FF8080) | `#FF8080` |
| Operators           | ![](https://img.shields.io/badge/%20-65737E?style=flat-square&color=65737E) | `#65737E` |
| Functions           | ![](https://img.shields.io/badge/%20-FFFFFF?style=flat-square&color=FFFFFF) | `#FFFFFF` |

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
