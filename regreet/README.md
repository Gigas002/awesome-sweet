# Sweet-Regreet

Instruction on how to use `Sweet` theme with [regreet](https://github.com/rharish101/ReGreet) greeter

## Requirements

- Sweet GTK theme: [Sweet-gtk](https://github.com/Gigas002/Sweet-gtk) ([PKGBUILD](../PKGBUILDs/sweet-gtk-theme-git))
- Sweet cursors: [Sweet-cursors](https://github.com/Gigas002/Sweet-cursors) ([PKGBUILD](../PKGBUILDs/sweet-cursors-git))
- Sweet folder icons: [Sweet-folders](https://github.com/Gigas002/Sweet-folders) ([PKGBUILD](../PKGBUILDs/sweet-folders-git))

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

