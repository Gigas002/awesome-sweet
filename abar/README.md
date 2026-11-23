# Sweet-abar

Sweet theme for [abar](https://github.com/Gigas002/abar) Wayland status bar

## Requirements

**Optional**

- `NotoSans Nerd Font`, Sweet's default font
- Candy icons ([aur](https://aur.archlinux.org/packages/candy-icons-git)), e.g. with `XDG_ICON_THEME=candy-icons`

## Installation

Copy theme file to abar's themes directory: `~/.config/abar/themes/Sweet.toml`

Then, set it in `~/.config/abar/config.toml` (see [example](example/config.toml)):

```toml
[base]
font_name = "NotoSans Nerd Font"
font_size = 14
theme = "Sweet.toml"
```

Or pass it once: `abar --theme ~/.config/abar/themes/Sweet.toml`

## Showcase

![](assets/screenshot.png)
