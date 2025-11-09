# 🎒 MyDadsSoft's Backpack Plugin

A lightweight, fast, and intuitive **Backpack plugin** for **Paper 1.21.10**  
that gives players a **GUI-based portable inventory** — simple, clean, and server-friendly.

---

## 🧩 Features

✅ **Open Anywhere** — players can use `/bp` or `/backpack` to open their backpack GUI  
✅ **Persistent Storage** — items are saved per player even after restarts  
✅ **Custom GUI** — shows a player-friendly inventory window  
⚡ **Coming Soon:** Permissions support and `/backpack give` command  

---

## 🧱 Commands

| Command | Description |
|----------|-------------|
| `/bp` | Opens your backpack GUI |
| `/backpack` | Same as `/bp` — opens your backpack |
| `/backpack reload` | Reloads plugin data (will be added later in the future) |

---

## 💾 Data Storage

Backpacks are stored per player using their **UUID** as the key in a YAML file.  

Example of saved data:

```yaml
60ec0ccb-0a4a-45d0-aae7-7b49c5da839d:
  contents:
    - id: minecraft:sticky_piston
      count: 64
    - id: minecraft:tnt
      count: 64
    - id: minecraft:totem_of_undying
      count: 1
    - null
    - null
    - id: minecraft:iron_shovel
      count: 1
      damage: 135
    # ... more items ...
