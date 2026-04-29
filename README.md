# config-vscode

A collection of [VS Code](https://code.visualstudio.com/) / [Cursor](https://cursor.com/) color themes, forked and adapted for local use.

## Themes

| Theme | Based on |
|-------|----------|
| **Cursor Dark** | [CedricVerlinden/cursor-dark](https://github.com/CedricVerlinden/cursor-dark) — Cursor editor theme repackaged for VS Code |
| **Cursor Dark Core** | [imzivko/cursor-dark-core](https://github.com/imzivko/cursor-dark-core) — Minimal Cursor Dark port for VS Code |
| **Miasma** | [OldJobobo/omarchy-miasma-theme](https://github.com/OldJobobo/omarchy-miasma-theme) — Base16 Miasma color theme |

## Installation

Each theme is a standalone VS Code extension. To install one locally:

```sh
cd themes/<theme-name>
code --install-extension .
```

Or package it first with [vsce](https://github.com/microsoft/vscode-vsce):

```sh
npx @vscode/vsce package
code --install-extension *.vsix
```
