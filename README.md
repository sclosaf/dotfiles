# dotfiles

My Linux configs, themed with [Nord](https://www.nordtheme.com/).

## Setups

- **`01-hyprlandDots/00-default`**: full Hyprland setup with Waybar, Hyprlock, Hypridle, Wlogout, Kitty, Zsh, Neovim, Btop, Cava and Fastfetch
- **`01-hyprlandDots/01-minimal`**: lightweight Hyprland with Kitty, Zsh and Neovim
- **`00-gnomeDots`**: Kitty, Zsh and Neovim for GNOME

## Install

> ⚠️ Made for Arch Linux. The scripts overwrite your files in `~/.config`, so back them up first.

```bash
git clone https://github.com/sclosaf/dotfiles.git
cd dotfiles/01-hyprlandDots/00-default/scripts   # or another setup

./installPackage.sh   # packages
./installFonts.sh     # fonts
./install.sh          # copy the configs
```
