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

## 🪟 Window Management (Rectangle) — Tiling Modes

Two ways to activate tiling — both use the same keys inside:

> [!TIP]
> **`Caps Lock + t`** (lowercase) = **one-shot**: tile one window, then auto-exits.
> **`Caps Lock + T`** (uppercase) = **toggle mode**: stays active until you press `Caps Lock` alone.

### Mode Triggers

| Key | Mode | Behaviour |
| :---: | :--- | :--- |
| **`Caps Lock + t`** | One-shot | Tile once → auto-exits |
| **`Caps Lock + T`** | Toggle | Stays on until `Caps Lock` exits |
| **`Caps Lock`** (alone, in toggle mode) | — | Exit tiling mode |

### Halves — `H J K L`

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`H`** | Left Half | `⌃ + ⌥ + ←` |
| **`L`** | Right Half | `⌃ + ⌥ + →` |
| **`K`** | Top Half | `⌃ + ⌥ + ↑` |
| **`J`** | Bottom Half | `⌃ + ⌥ + ↓` |

### Quarters — spatially arranged around `H J K L`

```
  Y   U        top-left   top-right
  H   L   →   (home row)
  B   N        bottom-left  bottom-right
```

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`Y`** | Top Left | `⌥ + ⇧ + ←` |
| **`U`** | Top Right | `⌥ + ⇧ + →` |
| **`B`** | Bottom Left | `⌃ + ⌥ + J` |
| **`N`** | Bottom Right | `⌃ + ⌥ + K` |

### Size & Restore

| Key | Action | Rectangle Shortcut |
| :---: | :--- | :--- |
| **`Space`** | Maximize | `⌃ + ⌥ + ↵` |
| **`R`** | Restore / Undo | `⌃ + ⌥ + ⌫` |

---

## 🌐 Browser Navigation

For Vim-like navigation in web browsers, use the [Vimium](https://github.com/philc/vimium) extension.
