<!-- Banner -->
<p align="center">
  <img src="assets/banner.png" alt="linux-keyboard-mouse Banner" width="100%">
</p>

<h1 align="center">⌨️ linux-keyboard-mouse</h1>

<p align="center">
Turn your keyboard into a complete mouse on Linux.
</p>

<p align="center">
A modern, open-source toolkit for controlling the mouse entirely from the keyboard.
Built for accessibility, productivity, and situations where a mouse or touchpad isn't available.
</p>

<p align="center">

![License](https://img.shields.io/github/license/GLTCH2434/linux-keyboard-mouse)
![GitHub stars](https://img.shields.io/github/stars/GLTCH2434/linux-keyboard-mouse?style=social)
![GitHub issues](https://img.shields.io/github/issues/GLTCH2434/linux-keyboard-mouse)
![GitHub last commit](https://img.shields.io/github/last-commit/GLTCH2434/linux-keyboard-mouse)
![Platform](https://img.shields.io/badge/platform-Linux-blue)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04%2B-E95420)

</p>

---

## Overview


**linux-keyboard-mouse** is an open-source toolkit that lets you control your mouse entirely from your keyboard on Linux.

It began as a practical solution for using a computer without a mouse or touchpad, but its long-term goal is to become a unified keyboard-to-mouse toolkit that supports multiple layouts, multiple remapping backends, and an easy-to-use installation experience.

Unlike repositories that provide a single remapping configuration, this project focuses on providing a complete, well-documented solution with reusable layouts, installation utilities, customization guides, and community contributions.

Whether you're replacing a broken mouse, improving accessibility, or simply prefer keyboard-driven workflows, **linux-keyboard-mouse** aims to provide a reliable and extensible solution.

---

## Why this project?

## Why this project?

Using a keyboard to control the mouse isn't just a convenience—it can be a necessity. **linux-keyboard-mouse** is designed to help in a variety of real-world situations, including:

- 🖱️ Your mouse has stopped working.
- 💻 Your laptop touchpad is broken or unreliable.
- ♿ You need an accessible, keyboard-first way to navigate your system.
- ⌨️ You prefer keeping your hands on the keyboard while working.
- 🧪 You're working on a kiosk, embedded, or headless system where a mouse isn't practical.
- 🚀 You enjoy productivity-focused workflows and keyboard shortcuts.

---

# Features

## Current

- Keyboard-controlled mouse movement
- Modifier-based controls using **Right Alt**
- Mouse movement (WASD)
- Left and right click
- Vertical scrolling
- Easy customization
- Beginner-friendly documentation
- Open-source
- Ubuntu 22.04+ support

---

## Planned

- Multiple keyboard layouts
- keyd support
- xremap support
- ydotool backend
- Installer script
- Backup & restore utilities
- Community layouts
- GUI installer
- Layout generator
- Custom layout editor

---

# Current Default Layout

> Hold **Right Alt** while using the keys below.

| Keys | Action |
|------|--------|
| Right Alt + W | Move Up |
| Right Alt + A | Move Left |
| Right Alt + S | Move Down |
| Right Alt + D | Move Right |
| Right Alt + J | Left Click |
| Right Alt + I | Right Click |
| Right Alt + T | Scroll Up |
| Right Alt + G | Scroll Down |

---

# Keyboard Layout

```text
              Hold Right Alt

              W
              ↑

      A   ←   •   →   D

              ↓
              S


Clicks

Right Alt + J  → Left Click
Right Alt + I  → Right Click


Scrolling

Right Alt + T  → Scroll Up
Right Alt + G  → Scroll Down

```
---

# Supported Backends

| Backend | Status |
|----------|--------|
| Input Remapper | ✅ Current |
| keyd | 🚧 Planned |
| xremap | 🚧 Planned |
| ydotool | 🚧 Planned |

---

# Repository Structure

```text
linux-keyboard-mouse/
│
├── assets/
│   ├── banner.png
│   ├── logo.svg
│   ├── demo.gif
│   └── layout.svg
│
├── docs/
│   ├── installation.md
│   ├── layouts.md
│   ├── customization.md
│   ├── troubleshooting.md
│   ├── faq.md
│   └── roadmap.md
│
├── presets/
│   ├── input-remapper/
│   ├── keyd/
│   ├── xremap/
│   └── ydotool/
│
├── scripts/
│   ├── install.sh
│   ├── uninstall.sh
│   ├── backup.sh
│   └── restore.sh
│
├── screenshots/
│
├── .github/
│
├── README.md
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── LICENSE
└── .gitignore
```

---

# Installation

Detailed installation instructions are available in:

```
docs/installation.md
```

At the moment, the project uses **Input Remapper** as its backend.

Future releases will provide automated installation scripts and support additional backends.

---

# Usage

After importing the provided preset into Input Remapper:

1. Select your keyboard.
2. Load the provided preset.
3. Apply the preset.
4. Start using your keyboard as a mouse.

Customization instructions are available in:

```
docs/customization.md
```

---

# Screenshots

Screenshots and demonstrations will be added as the project evolves.

Planned assets include:

- Desktop preview
- Keyboard layout illustration
- Animated demo
- Installation walkthrough
- Configuration examples

---

# Documentation

Comprehensive documentation is available inside the **docs/** directory.

- Installation
- Layouts
- Customization
- Troubleshooting
- FAQ
- Roadmap

The documentation is written for both beginners and experienced Linux users.

---

# Roadmap

## Version 1.0

- Input Remapper backend
- WASD layout
- Mouse clicks
- Mouse scrolling
- Documentation
- Screenshots

## Version 1.1

- IJKL layout
- Vim layout
- Arrow-key layout
- Left-handed layout
- Movement tuning guide

## Version 1.2

- Installer
- Uninstaller
- Backup utility
- Restore utility

## Future

- keyd backend
- xremap backend
- ydotool backend
- GUI installer
- Layout generator
- Community presets
- Plugin architecture

---

# Contributing

Contributions are welcome.

Whether you want to:

- improve documentation
- add layouts
- support another backend
- fix bugs
- improve accessibility
- create artwork
- improve scripts

please read:

```
CONTRIBUTING.md
```

before opening a Pull Request.

---

# Philosophy

This repository is designed to become more than a collection of remapping presets.

The goal is to provide a well-documented, extensible, and community-driven toolkit for keyboard-based mouse control on Linux.

Every addition should improve usability, accessibility, and maintainability while keeping the project approachable for new users.

---

# License

This project is licensed under the MIT License.

See the **LICENSE** file for details.

---

# Acknowledgements

This project builds upon the excellent Linux input ecosystem, including tools such as:

- Input Remapper
- keyd
- xremap
- ydotool

Thanks to the maintainers and contributors of these projects for making keyboard customization on Linux possible.

---

# Star the Project ⭐

If this project helps you, consider giving it a star on GitHub.

It helps others discover the project and supports future development.

---

<p align="center">

Made with ❤️ for the Linux community.

</p>
