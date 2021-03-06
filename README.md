# Dotfiles for my Arch Linux system
A gruvbox-themed Arch Linux *rice*.

## Details
### System Information
- Distro: Arch Linux
- Window Manager: `i3-gaps`

### Screenshots

![screenshot](/screenshots/screenshot1.png)
![screenshot](/screenshots/screenshot2.png)
![screenshot](/screenshots/screenshot3.png)
![screenshot](/screenshots/screenshot4.png)

## Packages used
- Application launcher: `rofi`
- Shell: `bash`
- Terminal emulator: `kitty`
- File Manager: `ranger`
- PDF Viewer: `zathura`
- Status bar: `polybar`
- Default browser: `Brave`
- System info fetch: `fet.sh`
- Display Manager: `lightdm`
- Compositor: `picom`
- For dotfiles management: `GNU Stow`
- Text editor: `neovim`
- Lockscreen: `betterlockscreen`

## Fonts installed
Most fonts are from [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts).
- Source Code Pro
- Iosevka
- Hack
- JetBrains Mono

## Wallpaper
- [Link to original artist](https://www.artstation.com/gharly)
- [Wallpaper link](https://imgur.com/a/pua0dYx)

# Miscellaneous
### Other packages and dependencies used
- [`polybar-themes`](https://github.com/adi1090x/polybar-themes) for polybar
- [`powerline-shell`](https://github.com/b-ryan/powerline-shell) for prompt style for shell

## To do
- [x] Install GNU Stow
- [x] Configure Git
- [x] Configure i3
- [x] Configure polybar (waiting for update)
    - [ ] Edit Battery Module (add charging and discharging animation)
- [x] Configure rofi
- [x] Configure nvim
    - [x] LSPConfig
	- [x] Treesitter
	- [ ] Telescope
    - [x] Port nvim config to lua
- [x] Configure bash
- [x] Configure ranger
- [ ] Configure kitty terminal
    - [x] Fix fonts in terminal

## Issues
- Battery module in polybar not working unless I reload i3 and polybar configuration.
