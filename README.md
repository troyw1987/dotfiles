# Info:
- **This config is for my Hyprland desktop**
- All of the software required is in the packages tab
- It's themed in catppuccin

# Packages:
```bash
sudo pacman -S btop neovim zsh waybar kitty cliphist ripgrep jq npm unzip noto-fonts noto-fonts-cjk noto-fonts-emoji noto-fonts-extra nerd-fonts 
yay -S vencord ttf-vista-fonts

git clone https://github.com/NvChad/NvChad ~/.config/nvim --depth 1 && nvim
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

```

# Usage:
- Git clone this repo
- cp into stow folder
- run `stow --target=$HOME .`
- cp into manually install folder
- copy files into the correct places

