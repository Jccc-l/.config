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

- zsh
- grub
- efibootmgr
- os-prober
- acpi
- ark
- chromium
- google-chrome
- alacritty
- base-devel
- bc
- bat
- baidunetdisk-bin
- bluez
- bluez-utils
- btrfs-props
- calibre
- clang
- dolphin
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
- gotop
- gtop
- htop
- gpm
- steam
- hmcl
- man-pages-zh_cn
- mpv
- nekoray-bin
- neovim
- network-manager-applet
- networkmanager
- npm
- nodejs
- noto-fonts-emoji
- ntfs-3g
- okular
- obs-studio
- openssh
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
- zip
- unzip
- ripgrep
- lsd
- todesk-bin
- ueberzug
- vim
- visual-studio-code-bin
- w3m
- wget
- wpa_supplicant
- xbindkeys
- xclip
- xorg
- xorg-xinit
- adobe-source-code-pro-fonts
- adobe-source-han-sans-cn-fonts
- noto-fonts-emoji
