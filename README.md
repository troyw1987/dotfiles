# Info:
- **This config is for my Hyprland desktop**
- Most of the software configured is in the .config folder
- It's themed in catppuccin

# Packages:
```bash
sudo pacman -S btop neovim zsh waybar kitty jq npm unzip noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra nerd-fonts 
sudo yay -S vencord

git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

# Usage:
- Git clone this repo
- cp into stow folder
- run `stow --target=$HOME .`
- cp into manually install folder
- mv files into the correct places

