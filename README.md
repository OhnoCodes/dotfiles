# dotfiles

This repository contains my personal terminal configuration files for a customized development environment on Pop!\_OS. It includes configurations for:

- **ZSH** (with Oh My Zsh + Powerlevel10k)
- **Alacritty** terminal emulator
- **Tmux** (terminal multiplexer)
- **Symlink Setup** for centralized config management
- Fully customized theming (colors, prompt, icons, transparency)


---

## Contents

- `.zshrc` — Main ZSH config file
- `.p10k.zsh` — Powerlevel10k prompt theme customization
- `.tmux.conf` — tmux configuration (status bar colors, keybindings)
- `alacritty.yml` — Alacritty color theme and font settings

---

## Features

- Custom color schemes using hex values
- Blood red + Plum + Midnight Blue theme across prompt and status bars
- Transparent terminal background variable in alacritty.yml
- Enhanced ZSH history, aliasing, and visual enhancements via `powerlevel10k`
- Persistent setup using **symlinks** to maintain source-controlled configs

---

## System

- OS: Pop!\_OS (NVIDIA)
- Shell: ZSH with Oh My Zsh
- Terminal: Alacritty
- Multiplexer: tmux

---

## Symlink Setup

Configuration files are symlinked from this repo to their respective locations:

```bash
ln -sf ~/dotfiles/.zshrc ~/.zshrc
ln -sf ~/dotfiles/.p10k.zsh ~/.p10k.zsh
ln -sf ~/dotfiles/.tmux.conf ~/.tmux.conf
ln -sf ~/dotfiles/alacritty.yml ~/.config/alacritty/alacritty.yml
