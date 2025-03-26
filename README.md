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

- Compositors: `hyprland`
- Launch menus: `rofi`, `tofi`, `anyrun`, `onagre`, `kickoff`
- Terminal-related: `kitty`, `alacritty`, `windows-terminal`, `foot`, `zellij`, `oh-my-posh`, `starship`, `yazi`
- Bars: `waybar`, `ashell`
- DM/Greeters: `regreet`
- Notifications: `dunst`
- Lock screen: `swaylock`, `hyprlock`
- Logout: `wlogout`, `wleave`
- Image viewers: `oculante`
- Editors: `nano`, `micro` (wip), `zed` (planned?), `helix` (planned?)

### PKGBUILDs

These are the `PKGBUILD`s I use on my system. I don't think these are appropriate for everyone, so these are not in AUR

- sweet-cursors-git: based on my [cursors](https://github.com/Gigas002/Sweet/tree/cursors) branch for with minor improvements to cursor generating process. Also adds new `.svg` cursors for `plasma6`
- sweet-cursors-hyprcursor-git: based on the same branch as `sweet-cursors-git`. Creates [hyprcursors](https://github.com/hyprwm/hyprcursor)
- sweet-folders-git: based on official branch with [minor fix](https://github.com/EliverLara/Sweet-folders/pull/21) for dolphin
- sweet-gtk-theme-git: based on official `nova` branch with no changes
- sweet-kde-theme-git: based on my heavily [modified](https://github.com/Gigas002/Sweet-kde/tree/plasma-6-migration) version of `Sweet` and `Sweet-kde` repos, merged into one, containing only `kde`-related code, plus some `plasma6` migration stuff
- sweet-konsole-git: based on same branch as `sweet-kde-theme-git`
- sweet-kvantum-git: based on same branch as `sweet-kde-theme-git`
- sweet-sddm-git: based on same branch as `sweet-kde-theme-git`

## Contributing

### I know nothing about theming

Hey, me no designer either!

You can try out looking at already implemented examples and do trial-and-error until you're happy with the results. I also recommend installing [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) vs code plugin, so you can see your colors right in text editor.

Also, for a reference you should take a look at the original theme's color schemes, e.g. use [konsole theme](https://github.com/EliverLara/Sweet/blob/nova/kde/konsole/Sweet.colorscheme) for other terminal emulators, like `foot`.

### I don't want to push my theme here/I know great theme in a different repo/App doesn't need theme, but can make usage of GTK or Kvantum

And that's great too! You can just provide the `README.md` file with instructions on how-to the theme for an app you're using. See `regreet`'s `README.md` file for a similar example.

### Rules

You can add theme or instructions for ANY app you like. Just provide a simple `README.md` file with your PR please. Refer to `alacritty` or `hyprland` themes here for an example of desired `README` file structure. You can basically just copy it's contents and replace with your PR stuff.

Also, since original theme uses capitalized name `Sweet` (not `sweet` or `SWEET`, etc), please keep that formatting in your themes names. Sorry about that.
