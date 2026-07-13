# ⌨️ linux-keyboard-mouse

A simple Linux keyboard-to-mouse configuration using **Input Remapper**.

Control your mouse cursor, clicks, and scrolling using only your keyboard.  
Designed for users who want a mouse-free workflow, need an alternative input method, or simply enjoy keyboard-based control.

---

## Features

- 🖱️ Control the mouse cursor using your keyboard
- 🐢 Precise cursor movement
- ⚡ Fast cursor movement using **Right Alt + M**
- 🖱️ Left and right mouse clicks
- 📜 Vertical scrolling
- ⌨️ Uses **Right Alt** as a modifier to preserve normal typing
- ⚙️ Easy to customize using Input Remapper

---

## Keyboard Layout

All mouse controls require holding the **Right Alt** key.

### Cursor Movement

| Keys | Action |
|------|--------|
| Right Alt + W | Move cursor up |
| Right Alt + A | Move cursor left |
| Right Alt + S | Move cursor down |
| Right Alt + D | Move cursor right |

### Fast Cursor Movement

| Keys | Action |
|------|--------|
| Right Alt + M + W | Move cursor up (fast) |
| Right Alt + M + A | Move cursor left (fast) |
| Right Alt + M + S | Move cursor down (fast) |
| Right Alt + M + D | Move cursor right (fast) |

### Mouse Buttons

| Keys | Action |
|------|--------|
| Right Alt + J | Left Click |
| Right Alt + I | Right Click |

### Scrolling

| Keys | Action |
|------|--------|
| Right Alt + T | Scroll Up |
| Right Alt + G | Scroll Down |

> **Tip:** Hold **Right Alt + M** while using **WASD** for faster cursor movement across the screen.

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
| Right Alt + W/A/S/D | Move cursor |
| Right Alt + M + W/A/S/D | Fast cursor movement |
| Right Alt + J | Left click |
| Right Alt + I | Right click |
| Right Alt + T | Scroll up |
| Right Alt + G | Scroll down |

When **Right Alt** is not pressed, the keyboard behaves normally.

---

## Customization

The keyboard layout can be customized using **Input Remapper**.

You can change:

- Movement keys
- Click keys
- Scroll keys
- Modifier key
- Mouse behavior settings

The provided layout is only a default configuration. Feel free to modify it to match your workflow.

For detailed customization instructions, see:

[Customization Guide](docs/customization.md)

---

## Screenshots

Screenshots and demonstrations will be added here.

Planned examples:

- Input Remapper configuration
- Keyboard layout reference
- Demo of keyboard-controlled mouse movement

---

## License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

This project uses:

- [Input Remapper](https://github.com/sezanzeb/input-remapper) — for keyboard-to-mouse remapping functionality.

Thanks to the developers and contributors who make Linux input customization possible.


