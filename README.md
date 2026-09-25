# My Zed Editor Configuration

Personal [Zed](https://zed.dev) configuration: `settings.json`, `keymap.json`, and a custom theme.

## Setup

Copy files to `~/.config/zed/`:

```sh
git clone https://github.com/Mauro-Bonilla/zed-config.git
cp zed-config/settings.json zed-config/keymap.json ~/.config/zed/
mkdir -p ~/.config/zed/themes
cp zed-config/themes/*.json ~/.config/zed/themes/
```

## Highlights

- Vim mode, VSCode base keymap, relative line numbers
- Tokyo Night Yellow / Resonance themes
- Font: JetBrainsMono Nerd Font, 65% window opacity
- LSPs: clangd, basedpyright + ruff, gopls, vtsls
- OpenRouter models (DeepSeek, GLM, Kimi) for the Agent panel