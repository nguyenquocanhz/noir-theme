# Noir Theme

Elegant dark color theme + file icon pack for Visual Studio Code. Built for developers who appreciate high-contrast readability with rich aesthetics.

## About the Project

**Noir Theme** is a customized collection of dark color themes and matching file icons for Visual Studio Code. Originally developed as an educational project for learning VS Code extension customization, theme JSON schemas, licensing, and publishing workflows, it offers 8 distinct theme temperatures ranging from pure pitch-black high contrast to a soft pastel cherry blossom (Sakura) theme.

This project is completely open-source, copyleft under the GPL-3.0 license, and free for learning purposes.

## Features

- **8 theme variants:**
  - `Noir`: The flagship dark mode.
  - `Noir (Soft)`: A softer contrast variant.
  - `Noir (Navy)`: A deep navy blue background.
  - `Noir (Vampiric)`: A deep crimson-dark theme.
  - `Noir (Sakura)`: Cherry blossom dark-pastel theme for anime fans (Wibu).
  - `Noir (Navy High Contrast)`: High contrast navy theme.
  - `Noir (Dark High Contrast)`: Pure pitch-black high contrast theme.
  - `Noir (Light High Contrast)`: Crisp light mode for day usage.
- Full semantic highlighting for TypeScript, JavaScript, Python, Go, Rust, PHP, CSS, HTML, C++, etc.
- Custom icon set with colored SVG icons (Noir Icons).

## Install

**Activate Theme:** `Ctrl+Shift+P` → `Preferences: Color Theme` → `Noir` or `Noir (Sakura)`

**Activate Icons:** `Ctrl+Shift+P` → `Preferences: File Icon Theme` → `Noir Icons`

## Build from Source

You can build the `.vsix` file to install it manually in VS Code:

```bash
# Install vsce tool
npm install -g @vscode/vsce

# Package extension
vsce package
```

## License

GPL-3.0-only © nguyenquocanhz
