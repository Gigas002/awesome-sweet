# Awesome Sweet

Community repo with some additional [Sweet](https://github.com/EliverLara/Sweet)-like themes for different applications, or instructions how to use this theme with your favorite apps

Feel free to contribute with your favorite app, or fix/change existing stuff

Let's create a unified place for all our `Sweet` applications!

## Supported

### Official

This is the list of stuff in the official `Sweet` theme repositories:

- [GNOME/GTK](https://github.com/EliverLara/Sweet) (2, 3, 4) theming
- KDE: [src 1](https://github.com/EliverLara/Sweet/tree/nova/kde), [src 2](https://github.com/EliverLara/Sweet-kde)
- [cursors](https://github.com/EliverLara/Sweet/tree/nova/kde/cursors)
- [Kvantum](https://github.com/EliverLara/Sweet/tree/nova/kde/Kvantum)
- [konsole](https://github.com/EliverLara/Sweet/tree/nova/kde/konsole)
- [SDDM](https://github.com/EliverLara/Sweet/tree/nova/kde/sddm)
- Icons: [candy-icons](https://github.com/EliverLara/candy-icons), [sweet-folders](https://github.com/EliverLara/Sweet-folders), [beautyline alternative](https://gitlab.com/garuda-linux/themes-and-settings/artwork/beautyline)
- [Firefox](https://github.com/EliverLara/firefox-sweet-theme)
- VSCode (*works with forks as well*): [colors](https://github.com/EliverLara/sweet-vscode), [icons](https://github.com/EliverLara/sweet-vscode-icons)
- [Wallpapers](https://github.com/EliverLara/Sweet/tree/nova/extras/Sweet-Wallpapers)

### This repo

At the moment, this repo contains following themes/instructions:

- Desktops/compositors: `cosmic`, `hyprland`, `niri`, `sway`
- Launch menus: `rofi`, `tofi`, `tofi-rs`, `anyrun`, `onagre`, `kickoff`
- Terminals: `alacritty`, `kitty`, `foot`, `windows-terminal`
- Terminal apps: `zellij`, `yazi`, `bottom`, `calendar-tui`, `tgrs`, `concord`
- Prompts: `starship`, `oh-my-posh`
- Bars: `waybar`, `ashell`, `abar`
- DM/Greeters: `regreet`, `ratgreet`, `tuigreet`
- Notifications: `dunst`, `poshanka`
- Lock screen: `swaylock`, `hyprlock`
- Logout: `wlogout`, `wleave`
- Image viewers: `oculante`
- Editors: `nano`, `micro`, `helix`
- Qt: `qt6ct`

Fonts used across the themes: `CaskaydiaCove Nerd Font Mono 14` for terminals, `NotoSans Nerd Font 14` for everything else

### Other community efforts

- [zed](https://zed-themes.com/themes/uoI4UhbiWof1tc3lPtuH9): install it into `~/.config/zed/themes`

### Forks

Maintained forks of the official themes, with fixes and Plasma 6 support:

- [Sweet-gtk](https://github.com/Gigas002/Sweet-gtk): GTK 3, GTK 4 and GNOME Shell
- [Sweet-kde](https://github.com/Gigas002/Sweet-kde): Plasma 6 color scheme, Plasma theme, window decorations and global theme
- [Sweet-kvantum](https://github.com/Gigas002/Sweet-kvantum): Kvantum application style
- [Sweet-cursors](https://github.com/Gigas002/Sweet-cursors): XCursor, KDE's scalable SVG cursors and hyprcursor
- [Sweet-folders](https://github.com/Gigas002/Sweet-folders): folder icons

### PKGBUILDs

These are the `PKGBUILD`s I use on my system, built from the forks above. I don't think these are appropriate for everyone, so these are not in AUR

- sweet-gtk-theme-git: [Sweet-gtk](https://github.com/Gigas002/Sweet-gtk), `master`
- sweet-kde-theme-git: [Sweet-kde](https://github.com/Gigas002/Sweet-kde), `master`
- sweet-kvantum-git: [Sweet-kvantum](https://github.com/Gigas002/Sweet-kvantum), `master`
- sweet-cursors-git: [Sweet-cursors](https://github.com/Gigas002/Sweet-cursors), `master`; XCursor and KDE's SVG cursors
- sweet-cursors-hyprcursor-git: [Sweet-cursors](https://github.com/Gigas002/Sweet-cursors), `master`; [hyprcursors](https://github.com/hyprwm/hyprcursor)
- sweet-folders-git: [Sweet-folders](https://github.com/Gigas002/Sweet-folders), `master`

## Contributing

### I know nothing about theming

Hey, me no designer either!

You can try out looking at already implemented examples and do trial-and-error until you're happy with the results. I also recommend installing [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) vs code plugin, so you can see your colors right in text editor.

Also, for a reference you should take a look at the original theme's color schemes, e.g. use [konsole theme](https://github.com/EliverLara/Sweet/blob/nova/kde/konsole/Sweet.colorscheme) for other terminal emulators, like `foot`.

### I don't want to push my theme here/I know great theme in a different repo/App doesn't need theme, but can make usage of GTK or Kvantum

And that's great too! You can just provide the `README.md` file with instructions on how-to the theme for an app you're using. See `regreet`'s `README.md` file for a similar example.

### Rules

You can add theme or instructions for ANY app you like. Just provide a simple `README.md` file with your PR please. Refer to `alacritty` or `niri` themes here for an example of desired `README` file structure. You can basically just copy it's contents and replace with your PR stuff.

Also, since original theme uses capitalized name `Sweet` (not `sweet` or `SWEET`, etc), please keep that formatting in your themes names. Sorry about that.
