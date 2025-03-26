# Sweet-Regreet

Instruction on how to use `Sweet` theme with [regreet](https://github.com/rharish101/ReGreet) greeter

## Requriments

- Sweet GTK theme ([aur](https://aur.archlinux.org/packages/plasma5-themes-sweet-full-git))
- Sweet cursors theme ([aur](https://aur.archlinux.org/packages/plasma5-themes-sweet-full-git))
- Sweet folder icons ([aur](https://aur.archlinux.org/packages/sweet-folders-icons-git))

## Installation

Add the following lines to your `/etc/greetd/regreet.toml`:

```toml
[GTK]
# Whether to use the dark theme
application_prefer_dark_theme = true

# Cursor theme name
cursor_theme_name = "Sweet-cursors"

# Icon theme name
icon_theme_name = "Sweet-Rainbow"

# GTK theme name
theme_name = "Sweet"
```

## Showcase

<!-- TODO: screenshot -->

![](assets/screenshot.png)
