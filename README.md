# Ghostty Theme: Grayscale

Port of the **Base16 Grayscale** (Dark & Light) color schemes for the [Ghostty](https://ghostty.org) terminal emulator.

## Themes Included

* `Grayscale Dark`
* `Grayscale Light`

## Installation

### 1. Copy the theme files to your Ghostty themes directory

* **macOS / Linux:**
  ```bash
  mkdir -p ~/.config/ghostty/themes
  cp "Grayscale Dark" "Grayscale Light" ~/.config/ghostty/themes/
  ```

### 2. Configure Ghostty

Add your preferred theme to your Ghostty configuration (`~/.config/ghostty/config`):

```conf
theme = Grayscale Dark
# or
theme = Grayscale Light
```

## Attribution & Credits

* Color scheme adapted from [RRethy/base16-nvim](https://github.com/RRethy/base16-nvim) (specifically `base16-grayscale-dark.vim` and `base16-grayscale-light.vim`), created by [Adam Regasz-Rethy](https://github.com/RRethy) under the MIT License.
* Original Base16 Grayscale color palettes designed by [Alexandre Gavioli](https://github.com/Alexx2/).
* Base16 architecture and concept by [Chris Kempson](https://github.com/chriskempson) and [Tinted Theming](https://github.com/tinted-theming).

## License

This project is licensed under the [MIT License](LICENSE).
