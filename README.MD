# Terminal colors for LazyVim

A lightweight configuration for **LazyVim** that forces the editor to strictly use your terminal's ANSI color palette

## What it does
This plugin is a "hard override" for your Neovim environment. It disables `termguicolors`, ensuring that Neovim pulls its color data directly from your terminal's **0-15** color slots 

Perfect for users of **Matugen**, **Pywal**, or custom **Kitty/Alacritty** themes who want their editor to match their shell perfectly

## Installation on LazyVim

To use this as a modular "drop-in" configuration, place the [Plugin](terminal-theme.lua) file in your plugins directory

**Path:** `~/.config/nvim/lua/plugins/terminal-colors.lua`
