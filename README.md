# ⌨️ linux-keyboard-mouse

A simple Linux keyboard-to-mouse configuration using **Input Remapper**.

Control your mouse cursor, clicks, and scrolling using only your keyboard.  
Designed for users who want a mouse-free workflow, need an alternative input method, or simply enjoy keyboard-based control.

---

## Features

- Move the mouse cursor using keyboard keys
- Left and right mouse click support
- Vertical scrolling
- Uses **Right Alt** as a modifier key to avoid interfering with normal typing
- Easy to customize using Input Remapper
- Lightweight and simple setup

---

## Keyboard Layout

All mouse controls require holding the **Right Alt** key.

### Mouse Movement

| Keys | Action |
|------|--------|
| Right Alt + W | Move cursor up |
| Right Alt + A | Move cursor left |
| Right Alt + S | Move cursor down |
| Right Alt + D | Move cursor right |

### Mouse Buttons

| Keys | Action |
|------|--------|
| Right Alt + J | Left click |
| Right Alt + I | Right click |

### Scrolling

| Keys | Action |
|------|--------|
| Right Alt + T | Scroll up |
| Right Alt + G | Scroll down |

---

### Quick Reference

```text
              Hold Right Alt

                    W
                    ↑

              A  ←  •  →  D

                    ↓
                    S


          J → Left Click
          I → Right Click

          T → Scroll Up
          G → Scroll Down
```

---

## Installation

### Requirements

- Linux system (Ubuntu 22.04+ recommended)
- Keyboard
- [Input Remapper](https://github.com/sezanzeb/input-remapper)

### Quick Setup

1. Install Input Remapper.

```bash
sudo apt update
sudo apt install input-remapper
```

2. Clone this repository.

```bash
git clone https://github.com/GLTCH2434/linux-keyboard-mouse.git
cd linux-keyboard-mouse
```

3. Import the preset from:

```
preset/
```

4. Open Input Remapper and enable the preset for your keyboard.

For a detailed installation guide, see : 

[Installation Guide](docs/installation.md)

---

## Usage

After enabling the preset in Input Remapper:

1. Hold the **Right Alt** key.
2. Use the mapped keys to control the mouse.

Example:

| Key Combination | Action |
|----------------|--------|
| Right Alt + W | Move cursor up |
| Right Alt + A | Move cursor left |
| Right Alt + S | Move cursor down |
| Right Alt + D | Move cursor right |
| Right Alt + J | Left click |
| Right Alt + I | Right click |
| Right Alt + T | Scroll up |
| Right Alt + G | Scroll down |

When **Right Alt** is not pressed, the keyboard behaves normally.


