# quuinnn/dotfiles
My personal dotfiles

**BTW if you clone this repo and cd into it then run the ls command, the .mozilla and .config directories are HIDDEN because they start with "." (my fault) so you have to run `ls -a` to show them**

This setup uses around 600-700MiBs RAM on idle on my 15693MiB (16GBs) 12th Gen Intel i5-1235U Arch Linux machine (11 cores, 4.400GHz) using the 6.8.4 Linux Kernel (5.x might have lesser RAM usage)

# RAM Prerequisites

pactl

polkit

gtk

qt6ct

hyprland-git (you really need the -git version or you'll have to edit out alot of stuff from "/.config/hypr/hyprland.conf")

hyprlock-git

hypridle-git

brightnessctl

trash-cli

starship

earlyoom

lsd (the program, not the drug although they're both amazing in their own ways)

a [nerd font](https://www.nerdfonts.com/) installed **(REALLY IMPORTANT)**

kitty

neovim

nix (use the [Nix Determinate installer](https://github.com/DeterminateSystems/nix-installer))

# Previews

All rights reserved to the copyright owners of the images used below

### - [AGS Dots](https://github.com/Aylur/dotfiles) (Wi-Fi name redacted)
![2024-03-10_17-48-18](https://github.com/fortunef/My-Arch-Install/assets/141419112/42ed12a5-89b6-4709-be46-81cb495f7c53)

### - Spotify w/ [Spicetify](https://spicetify.app/), the [Catppuccin Mocha](https://github.com/catppuccin/spicetify) theme, and a bunch of extensions
![2024-04-03_23-40-40](https://github.com/fortunef/dotfiles/assets/141419112/c6433461-e87d-4cb0-a87e-6011a07a1cdf)

### - [NVChad](https://nvchad.com/)
![2024-03-10_23-30-12](https://github.com/fortunef/My-Arch-Install/assets/141419112/92c3eb67-e05c-4179-bac6-4297da45131c)

### - [Kitty](https://sw.kovidgoyal.net/kitty/), [LSD](https://github.com/lsd-rs/lsd), and [Starship](https://starship.rs/)
![2024-03-10_23-31-47](https://github.com/fortunef/My-Arch-Install/assets/141419112/fe720c76-bff9-4e0a-8e40-c631a9466661)

### - Steam w/ [AdwSteamGTK](https://flathub.org/apps/io.github.Foldex.AdwSteamGtk) (Catppuccin Mocha)
![2024-04-03_23-38-20](https://github.com/fortunef/dotfiles/assets/141419112/febe7dbe-8843-4b0f-adab-99974914c531)

### - Firefox w/ [Arcticfox](https://github.com/sirlan-ff00ff/arcticfox-theme) and the [Tabliss](https://tabliss.io/) extension.
![2024-03-10_19-16-45](https://github.com/fortunef/My-Arch-Install/assets/141419112/8795a807-b594-43d2-b897-3add61e9249c)

# Credits | Dotfiles
### AGS:
https://github.com/Aylur/dotfiles

### Kitty:
https://github.com/catppuccin/kitty/ Mocha

### Grub:
https://github.com/catppuccin/grub/ Mocha

### GTK:
https://github.com/catppuccin/gtk Mocha

### Starship
Default

### Icon:
https://github.com/vinceliuice/Tela-circle-icon-theme Dracula

### Cursor:
https://github.com/ful1e5/Bibata_Cursor Classic

### Firefox:
https://github.com/sirlan-ff00ff/arcticfox-theme w/ [catppuccin/firefox](https://github.com/catppuccin/firefox) Mocha

### Dark Reader
https://github.com/catppuccin/dark-reader Mocha

### Steam:
https://flathub.org/apps/io.github.Foldex.AdwSteamGtk Theme: Catppuccin-Mocha, Window Controls: None, Controls Style: Dots, and the rest at default

### Neovim:
https://nvchad.com/ ~~(copy over [my chadrc](https://github.com/fortunef/My-Arch-Install/blob/main/.config/nvim/lua/custom/chadrc.lua))~~ NvChad has changed a bit (I should update it), change the theme in ~/.config/neovim/lua/chadrc.lua (or wherever the hell it is now) to catppuccin using a text editor. Also, add 
``` lua
vim.filetype.add({
  pattern = { [".*/hypr/.*%.conf"] = "hyprlang" },
})
```
to your init.lua, and run `:TSInstall hyprlang` for [hyprlang](https://hyprland.org/hyprlang/) syntax hilighting 

(the syntax highlighting has some mistakes, but it's better than none)

# License
This project is licensed under the MIT License. It allows you to modify this for any usage but with absolutely **ZERO** warranty. For more information, [read the license](https://github.com/fortunef/My-Arch-Install/blob/main/LICENSE).
