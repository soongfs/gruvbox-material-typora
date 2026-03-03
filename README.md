# Gruvbox Material for Typora

This folder contains a Typora theme port of the Vim theme in this repository.

## Theme choice

- Base palette: `material`
- Contrast: `medium`
- Available themes:
  - `gruvbox-material-dark.css`
  - `gruvbox-material-light.css`

Both files are standalone themes. They map the original palette tokens to Typora's writing area, source mode, code fences, blockquotes, tables, task lists, math blocks, and table of contents.

## Install

1. In Typora, open `Preferences` -> `Appearance` -> `Open Theme Folder`.
2. Copy `gruvbox-material-dark.css` and `gruvbox-material-light.css` into that theme folder.
3. Restart Typora.
4. Select one of:
   - `Themes` -> `gruvbox-material-dark`
   - `Themes` -> `gruvbox-material-light`

Typora's theme install flow and code fence theming rules are documented here:

- https://support.typora.io/About-Themes/
- https://support.typora.io/Code-Block-Styles/

## Structure

- [gruvbox-material-dark.css](/home/soongfs/gruvbox-material/typora/gruvbox-material-dark.css): standalone dark theme
- [gruvbox-material-light.css](/home/soongfs/gruvbox-material/typora/gruvbox-material-light.css): standalone light theme

## Customize

- Dark colors live in [gruvbox-material-dark.css](/home/soongfs/gruvbox-material/typora/gruvbox-material-dark.css).
- Light colors live in [gruvbox-material-light.css](/home/soongfs/gruvbox-material/typora/gruvbox-material-light.css).
- The source palette values come from [autoload/gruvbox_material.vim](/home/soongfs/gruvbox-material/autoload/gruvbox_material.vim).

If you want `hard` or `soft`, replace the `bg*` variables with the values from the matching palette block in `autoload/gruvbox_material.vim`. If you want `mix` or `original`, replace the accent colors and foreground colors in the same way.
