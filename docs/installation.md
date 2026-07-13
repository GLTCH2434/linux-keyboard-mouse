# Installation

This guide explains how to install and enable **linux-keyboard-mouse** using **Input Remapper**.

After completing this guide, you will be able to control your mouse using your keyboard.

---

## Requirements

Before installing, make sure you have:

- A Linux system (Ubuntu 22.04+ recommended)
- A working keyboard
- Internet access
- `sudo` privileges

---

## Install Input Remapper

`linux-keyboard-mouse` uses **Input Remapper** to convert keyboard inputs into mouse actions.

Install it using:

```bash
sudo apt update
sudo apt install input-remapper
```

After installation, open Input Remapper from your application menu.

---

## Download the Project

Clone the repository:

```bash
git clone https://github.com/GLTCH2434/linux-keyboard-mouse.git
```

Enter the project directory:

```bash
cd linux-keyboard-mouse
```

---

## Import the Preset

1. Open **Input Remapper**.
2. Select your keyboard device.
3. Open the preset management menu.
4. Import the preset from:

```
preset/
```

5. Save the imported preset.

---

## Enable the Preset

1. Select the imported preset.
2. Click **Apply**.
3. Make sure the preset is active.

The keyboard-to-mouse controls are now enabled.

---

## Test the Controls
## Test the Controls

Hold **Right Alt** and test:

| Keys | Action |
|------|--------|
| Right Alt + W | Move up |
| Right Alt + A | Move left |
| Right Alt + S | Move down |
| Right Alt + D | Move right |
| Right Alt + M + W | Move up (fast) |
| Right Alt + M + A | Move left (fast) |
| Right Alt + M + S | Move down (fast) |
| Right Alt + M + D | Move right (fast) |
| Right Alt + J | Left Click |
| Right Alt + I | Right Click |
| Right Alt + T | Scroll Up |
| Right Alt + G | Scroll Down |

---

## Troubleshooting

If the controls do not work:

- Make sure Input Remapper is running.
- Verify the correct keyboard device is selected.
- Check that the preset is active.
- Try restarting Input Remapper.

For customization, see:

[Customization Guide](customization.md)
