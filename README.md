# 🚀 Vimac (Vim Your Mac)

Vimac brings **Vim-like navigation and system controls** to macOS using **Karabiner-Elements**. By remapping the physical **Caps Lock** key, standard home row keys are transformed into navigation, selection, and system commands.

> [!TIP]
> The physical **Caps Lock** key acts as a dual-role **super-key**:
> - **Tap alone:** Sends `Escape` (perfect for Vim users).
> - **Hold down:** Activates the Vim navigation and selection layer.

---

## ⌨️ Karabiner Keybindings

All keybindings below are active while holding the **Caps Lock** key:

| Key | Action | Mapping |
| :---: | :--- | :--- |
| **`Caps Lock` (alone)** | Escape | `Escape` |
| **`\`` (backtick)** | Toggle normal Caps Lock | `Caps Lock` |
| **`H`** | Move Left | `←` |
| **`J`** | Move Down | `↓` |
| **`K`** | Move Up | `↑` |
| **`L`** | Move Right | `→` |
| **`U`** | Beginning of Line | `Home` |
| **`I`** | End of Line | `End` |
| **`F`** | Move Word Left | `⌥ + ←` |
| **`G`** | Move Word Right | `⌥ + →` |
| **`A`** | Select Character Left | `⇧ + ←` |
| **`S`** | Select Line Down | `⇧ + ↓` |
| **`D`** | Select Character Right | `⇧ + →` |
| **`W`** | Select Line Up | `⇧ + ↑` |
| **`Q`** | Select Word Left | `⇧ + ⌥ + ←` |
| **`E`** | Select Word Right | `⇧ + ⌥ + →` |

---

## 🪟 Window Management (Rectangle)

All keybindings below require holding **Caps Lock + Shift**:

> [!TIP]
> Mirrors Vim's mental model — lowercase motions move the **cursor**, Shift motions move the **window**.

### Halves

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`⇧ + H`** | Left Half | `⌥ + ←` |
| **`⇧ + L`** | Right Half | `⌥ + →` |
| **`⇧ + K`** | Top Half | `⌥ + ↑` |
| **`⇧ + J`** | Bottom Half | `⌥ + ↓` |

### Quarters

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`⇧ + U`** | Top Left | `⌥ + ⇧ + ←` |
| **`⇧ + I`** | Top Right | `⌥ + ⇧ + →` |
| **`⇧ + N`** | Bottom Left | `⌃ + ⌥ + J` |
| **`⇧ + M`** | Bottom Right | `⌃ + ⌥ + K` |

### Size & Restore

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`⇧ + F`** | Maximize | `⌥ + ⇧ + ↑` |
| **`⇧ + R`** | Restore | `⌃ + ⌥ + ⌫` |

---

## 🌐 Browser Navigation

For Vim-like navigation in web browsers, use the [Vimium](https://github.com/philc/vimium) extension.
