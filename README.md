# starship-cat-spacesuit

## Description

A Catppuccin-themed Starship prompt with rounded capsule segments. Providing the basics, but easily expandable for custom needs.

## Screenshots

*Rendered in [Ghostty](https://ghostty.org/) with [Fish](https://fishshell.com/), using the Catppuccin Mocha theme and [JetBrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads).*

<img width="1270" height="875" alt="Screenshot-2026-10-04_18-52-14" src="https://github.com/user-attachments/assets/d874986a-d94a-45cf-a343-97944b0b018c" />


## Installation

1. Install [Starship](https://starship.rs/) if you have not already.
2. Copy `starship.toml` to `~/.config/starship.toml`.
3. Ensure your terminal uses a [Nerd Font](https://www.nerdfonts.com/), since the capsules and icons rely on its glyphs. 
4. Add `eval "$(starship init <your-shell>)"` to your shell configuration file.

## Customization

New segments are easy to add. Each capsule follows the same pattern: a left cap, styled content, and a right cap, using any colour from the bundled Catppuccin palettes. See the commented template in the configuration file.

## Contribution

Do not hesitate to open a PR if you want to contribute, whether for a new language capsule, another Catppuccin flavour, or a refinement of the existing segments. Issues are equally welcome.
