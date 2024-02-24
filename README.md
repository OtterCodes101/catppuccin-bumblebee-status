<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for  <a href="https://github.com/tobi-wan-kenobi/bumblebee-status">bumblebee-status</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/OtterCodes101/catppuccin-bumblebee-status/stargazers"><img src="https://img.shields.io/github/stars/OtterCodes101/catppuccin-bumblebee-status?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/OtterCodes101/catppuccin-bumblebee-status/issues"><img src="https://img.shields.io/github/issues/OtterCodes101/catppuccin-bumblebee-status?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/OtterCodes101/catppuccin-bumblebee-status/contributors"><img src="https://img.shields.io/github/contributors/OtterCodes101/catppuccin-bumblebee-status?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

## Usage

>Note: You may need to install a Powerline/Nerd Font in order to use this.

1. Clone the repository
2. `cd` into the repository
3. Copy the theme of your choice from the themes folder into `~/.config/bumblebee-status/themes` 
> (If you get `bash: ~/.config/bumblebee-status/themes: No such file or directory` or something similar, run `mkdir -p ~/.config/bumblebee-status/themes`)
4. Edit your i3 configuration to use the theme

example:

```
bar {
  colors {
    background         $base
    statusline         $text
    focused_statusline $text
    active_workspace   $base $text $blue
    focused_separator  $base
    focused_workspace  $base $base $green
    active_workspace   $base $base $blue
    inactive_workspace $base $base $surface1
    urgent_workspace   $base $base $surface1
    binding_mode       $base $base $surface1
  }
status_command bumblebee-status -m cpu memory disk battery time -t catppuccin-mocha
}
```

## 💝 Thanks to

- [OtterDev](https://github.com/OtterCodes101)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>