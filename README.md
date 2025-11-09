# 🎒 MyDadsSoft's Backpack Plugin

A lightweight, fast, and intuitive **Backpack plugin** for **Paper 1.21.10**  
that gives players a **GUI-based portable inventory** — simple, clean, and server-friendly.

---

## 🧩 Features

✅ **Open Anywhere** — players can use `/bp` or `/backpack` to open their backpack GUI  
✅ **Customizable Sizes** — easily change how many slots backpacks have  
✅ **Persistent Storage** — items stay safe even after restarts or reloads   
✅ **Configurable GUI Titles & Items** — match your server’s theme and style  
✅ **Optimized for Performance** — built specifically for the **Paper 1.21.10 API**  
⚡ **Coming Soon:** Permissions support to control who can use or access backpacks  

---

## 🧱 Commands

| Command | Description |
|----------|-------------|
| `/bp` | Opens your backpack GUI |
| `/backpack` | Same as `/bp` — opens your backpack |
| `/backpack reload` | Reloads the plugin configuration # Coming soon |

---

## ⚙️ Configuration Example

```yaml
# config.yml

backpack:
  size: 27              # Number of slots (9, 18, 27, 36, 45, 54)
  title: "&6Your Backpack"
  open-sound: "BLOCK_CHEST_OPEN"
  save-on-close: true
  item:
    material: "CHEST"
    name: "&eBackpack"
    lore:
      - "&7Right-click to open your backpack"
      - "&7or type &f/bp"
