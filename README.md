# Dotfile

## zsh

### Plugins:
- [zsh-you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use)
- [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [powerlevel10k](https://github.com/romkatv/powerlevel10k)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions.git)

### Zsh Vi-Mode

Set Vi-Mode instead of emacs-mode

```zsh
bindkey -v
```

```zsh
# Set keymaps for Vi-Mode
bindkey -M vicmd keys action
# 'keys' is the key combination to bind, and 'action' is the corresponding action or command.
```

See [Zsh Line Editor - Movements](https://zsh.sourceforge.io/Doc/Release/Zsh-Line-Editor.html#Movement)

E.G.
```zsh
# Map 'k' to backward-char
bindkey -M vicmd 'k' backward-char
```

## Arch Packages

- acpi
- adobe-source-code-pro-fonts
- adobe-source-han-sans-cn-fonts
- alacritty
- ark
- baidunetdisk-bin
- base-devel
- bat
- bc
- bluez
- bluez-utils
- btrfs-props
- calibre
- chromium
- clang
- dolphin
- efibootmgr
- fcitx5
- fcitx5-chinese-addons
- fcitx5-nord
- fcitx5-pinyin-moegirl
- fcitx5-zhwiki
- fd
- feh
- ffmpeg
- flameshot
- fzf
- google-chrome
- gotop
- gpm
- grub
- gtop
- hmcl
- htop
- lsd
- man-pages-zh_cn
- mpv
- nekoray-bin
- neovim
- network-manager-applet
- networkmanager
- nodejs
- noto-fonts-emoji
- noto-fonts-emoji
- npm
- ntfs-3g
- obs-studio
- okular
- openssh
- os-prober
- p7zip
- picom
- polkit-kde-agent
- pulseaudio
- pulseaudio-bluetooth
- python-pynvim
- qbittorrent
- qqmusic-electron
- ranger
- rar
- ripgrep
- steam
- todesk-bin
- ueberzug
- unzip
- vim
- visual-studio-code-bin
- w3m
- wget
- wpa_supplicant
- xbindkeys
- xclip
- xorg
- xorg-xinit
- zip
- zsh
