# Stormwave for Omarchy

Stormwave is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`stormwave`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `stormwave`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `stormwave`
- **Omarchy theme repo:** `omarchy-stormwave-theme`

The theme split works like this:

- Omarchy repo = system/app theme assets
- Neovim theme = editor colorscheme
- both are intended to match visually

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

Omarchy applies the theme files in this repo to supported applications and desktop components. Neovim should load the matching `stormwave` colorscheme separately.

## Naming convention

- **Omarchy repo:** `omarchy-stormwave-theme`
- **Neovim theme:** `stormwave`

## Goal

Stormwave is intended to give Omarchy and Neovim a single unified visual identity.
