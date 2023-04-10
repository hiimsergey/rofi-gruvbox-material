# <p align="center">Gruvbox Material Rofi theme (GTK version)</p>

### <p align="center">This branch is slightly different to match the <a href="https://github.com/TheGreatMcPain/gruvbox-material-gtk">corresponding GTK theme</a>.</p>

<p align="center">A simple Gruvbox Material <a href="https://github.com/davatorium/rofi">Rofi</a> color theme.</p>

<p align="center">Based on the <a href="https://github.com/sainnhe/gruvbox-material">Gruvbox Material</a> color palette.</p>

<p align="center">Credits to <a href="https://github.com/undiabler">@undiabler</a> for providing the basis that I shamelessly took and recolored.</p>

<p align="center">I used it to make my personal theme for my Gruvbox Material desktop.</p>

---

<p align="center"><img src="screenshot.jpg"/><blockquote>Font: <a href="https://www.jetbrains.com/lp/mono/">JetBrains Mono</a> 12px.</blockquote></p>

## Getting started
### Installation

1. Copy <a href="gruvbox-material.rasi">gruvbox-material.rasi</a> file to `~/.config/rofi/gruvbox-material.rasi`
2. Add the following lines to your rofi config (`~/.config/rofi/config.rasi`):
```
configuration {
    font: "JetBrains Mono 12";

    display-ssh:    "";
    display-run:    "";
    display-drun:   "";
    display-window: "";
    display-combi:  "";
    show-icons:     true;
}

@theme "~/.config/rofi/gruvbox-material.rasi"
```
