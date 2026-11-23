# Sweet-concord

Instruction on how to use `Sweet` theme with [concord](https://github.com/chojs23/concord), a terminal Discord client

## Requirements

- A terminal with a Sweet color scheme, e.g. [alacritty](../alacritty), [kitty](../kitty) or [foot](../foot)

## Installation

There's nothing to install: concord's default theme uses the terminal's colors (`terminal_default` and ANSI color names), so with a Sweet terminal it's Sweet already

To change single colors anyway, add highlight groups to `theme.toml` in concord's config directory (`~/.config/concord`), e.g. a Sweet selection:

```toml
[highlight.Selection]
background = "#c50ed2"
```

Run `concord --check-config` to see warnings about invalid entries
