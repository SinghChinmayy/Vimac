# Vimac

Vim-style navigation on macOS via Karabiner-Elements. `Caps Lock` is the super-key.

- Tap alone → `Escape`
- Hold → navigation layer

---

## Desktop Navigation

Hold `Caps Lock` + key:

| Key | → |
| :---: | :--- |
| `H` | ← |
| `J` | ↓ |
| `K` | ↑ |
| `L` | → |
| `U` | Home (line start) |
| `I` | End (line end) |
| `F` | Word ← |
| `G` | Word → |

**Selection** (hold `Caps Lock` + key):

| Key | → |
| :---: | :--- |
| `A` | Select char ← |
| `D` | Select char → |
| `W` | Select line ↑ |
| `S` | Select line ↓ |
| `Q` | Select word ← |
| `E` | Select word → |

**Other:**

| Key | → |
| :---: | :--- |
| `` ` `` | Toggle real Caps Lock |

---

## Window Tiling (Rectangle)

Two modes. Same keys inside both.

| Trigger | Mode | Exits when |
| :--- | :--- | :--- |
| `Caps Lock + t` | One-shot | After one action |
| `Caps Lock + T` | Toggle | `Caps Lock` alone |

**Halves:**

| Key | → | Rectangle shortcut |
| :---: | :--- | :--- |
| `H` | Left half | `^⌥←` |
| `L` | Right half | `^⌥→` |
| `K` | Top half | `^⌥↑` |
| `J` | Bottom half | `^⌥↓` |

**Quarters** (spatial layout):

```
Y  U   →  top-left   top-right
B  N   →  bottom-left  bottom-right
```

| Key | → | Rectangle shortcut |
| :---: | :--- | :--- |
| `Y` | Top-left | `^⌥U` |
| `U` | Top-right | `^⌥I` |
| `B` | Bottom-left | `^⌥J` |
| `N` | Bottom-right | `^⌥K` |

**Other:**

| Key | → | Rectangle shortcut |
| :---: | :--- | :--- |
| `Space` | Maximize | `^⌥↩` |
| `R` | Restore | `^⌥⌫` |

---

## Browser Navigation

Use [Vimium](https://github.com/philc/vimium) for Vim-style browser navigation.
