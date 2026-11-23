# Sweet-tgrs

Instruction on how to use `Sweet` theme with [tgrs](https://github.com/Gigas002/tgrs), a terminal Telegram client

## Requirements

- A terminal with a Sweet color scheme, e.g. [alacritty](../alacritty), [kitty](../kitty) or [foot](../foot)

## Installation

There's nothing to install: `tgrs` follows the terminal's colors (default foreground/background and the ANSI palette), so with a Sweet terminal it's Sweet already

To change single colors anyway, add highlight groups to `~/.config/tgrs/theme.toml`, e.g. a Sweet selection:

```toml
[highlight.SelectedRow]
background = "#c50ed2"
```
