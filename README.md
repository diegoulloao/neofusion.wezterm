<div align="center">
    <h1>
        <img src="https://i.ibb.co/87DhmZx/logo.jpg" width="110" />
        <br />neofusion.wezterm
    </h1>
</div>

<p align="center">
    <img src="https://img.shields.io/badge/Wezterm-4d49e5.svg?style=for-the-badge&logo=wezterm" alt="zsh-badge" />
</p>

<p align="center">
    Neofusion theme for <a href="https://wezfurlong.org/wezterm/" target="_blank">WezTerm</a> blending lava red and ice blue colors ✨
</p>

<p align="center">
    <img src="https://i.ibb.co/r6fjmrk/wezterm-1.png" alt="neofusion" />
    <hr/>
    <p><b><code>spotify-player</code></b></p>
    <img src="https://i.ibb.co/nkm5t0j/wezterm-2.png" alt="neofusion" />
    <hr/>
    <p><b><code>htop</code></b></p>
    <img src="https://i.ibb.co/Q95qLVG/wezterm-3.png" alt="neofusion" />
    <hr />
    <p><b><code>onefetch</code></b></p>
    <img src="https://i.ibb.co/4WMjHFz/wezterm-4.png" alt="neofusion" />
</p>

# Installation 📦

Add the following code to your `.wezterm.lua` config:

```lua
local wezterm = require("wezterm")
local config = wezterm.config_builder()

local neofusion_theme = {
  foreground = "#e0d9c7",
  background = "#070f1c",
  cursor_bg = "#e0d9c7",
  cursor_border = "#e0d9c7",
  cursor_fg = "#070f1c",
  selection_bg = "#ea6847",
  selection_fg = "#e0d9c7",
  ansi = {
    "#070f1c", -- Black (Host)
    "#ea6847", -- Red (Syntax string)
    "#ea6847", -- Green (Command)
    "#5db2f8", -- Yellow (Command second)
    "#2f516c", -- Blue (Path)
    "#d943a8", -- Magenta (Syntax var)
    "#86dbf5", -- Cyan (Prompt)
    "#e0d9c7", -- White
  },
  brights = {
    "#2f516c", -- Bright Black
    "#d943a8", -- Bright Red (Command error)
    "#ea6847", -- Bright Green (Exec)
    "#86dbf5", -- Bright Yellow
    "#5db2f8", -- Bright Blue (Folder)
    "#d943a8", -- Bright Magenta
    "#ea6847", -- Bright Cyan
    "#e0d9c7", -- Bright White
  },
}

return {
  -- set theme
  colors = neofusion_theme,

  -- rest...
}
```

# Getting the right diff colors ✅

Add the following lines to your `~/.gitconfig` file:

```bash
[color "diff"]
  new = cyan
```

# Ports ⭐

### `neofusion.nvim`

Neovim theme version. [Check it out!](https://github.com/diegoulloao/neofusion.nvim)

### `neofusion.iterm`

iTerm2 theme version. [Check it out!](https://github.com/diegoulloao/neofusion.iterm)

### `neofusion.alacritty`

Alacritty theme version. [Check it out!](https://github.com/diegoulloao/neofusion.alacritty)

### `neofusion.kitty`

Kitty theme version. [Check it out!](https://github.com/diegoulloao/neofusion.kitty)

### `neofusion.winterm`

Windows Terminal theme version. [Check it out!](https://github.com/diegoulloao/neofusion.winterm)

### `neofusion.bat`

Bat theme version [Check it out!](https://github.com/diegoulloao/neofusion.bat/)

### `neofusion.fzf`

FZF theme version [Check it out!](https://github.com/diegoulloao/neofusion.fzf/)

### `neofusion.k9s`

K9s theme version. [Check it out!](https://github.com/diegoulloao/neofusion.k9s)

### `neofusion-wallpapers`

Beautiful wallpapers that match your setup. [Check available resolutions](https://github.com/diegoulloao/neofusion-wallpapers?tab=readme-ov-file)

# Sponsor ❤️

Check out our awesome sponsor!

<div>
  <a href="https://github.com/NeckBeardPrince" target="_blank">
    <img src="https://avatars.githubusercontent.com/u/6558867" width="64" height="64" />
  </a>
</div>
