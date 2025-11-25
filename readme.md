# 🧙‍♂️ Rogue Dungeon

### **A Fast, Procedurally Generated Rogue-Lite That Runs in Your Terminal.**

*A polished CLI game built to demonstrate engineering clarity, systems thinking, and real-time UI design.*

---

![Demo GIF](dungeon.gif)


---

## 🚀 Why This Project Exists

**Rogue Dungeon** isn’t “just another terminal game.”
It’s a demonstration of:

* Real-time terminal UI engineering
* Complex state management
* Procedural map generation
* Turn-based combat systems
* Animation inside a CLI
* Architecture thinking & clean code design

The goal was simple:

> **Build something fun, technical, and uniquely impressive to recruiters.**
> Something more than just CRUD apps.

This game is the result.

---

# 🎯 What Makes It Stand Out

### ❇️ **Procedural dungeon generator**

Every run produces a new map using a controlled random-walk algorithm.

### ❇️ **Reactive ASCII interface**

Built using **Blessed** → interactive panels, borders, HP bar, enemies list, log feed.

### ❇️ **Turn-based combat with micro-animations**

Cells flash on hit, enemies chase intelligently, combat feels alive.

### ❇️ **Enemy AI (simple but effective)**

Goblins:

* Chase the player using Manhattan distance
* Attack when adjacent
* Wander if unaware

### ❇️ **Clean architecture & modularity**

Separated into:

* `dungeon.js` → world generation
* `game.js` → engine, UI, combat logic

This shows deliberate design choices — something recruiters love.

---

# 🖼️ Game Preview (ASCII)

```
###############################
#@....g...$.......###.........#
#.....###.....G...............#
#...T.....E....................#
###############################

 Stats:
 HP: #########--------- (11/20)
 ATK: 5
 Gold: 3

 Log:
 You hit goblin for 3 dmg.
 Goblin died.
```

---

# 🛠 Tech Stack

| Layer        | Tech                                |
| ------------ | ----------------------------------- |
| UI Rendering | Blessed (terminal UI framework)     |
| Game Engine  | Node.js (event-driven game loop)    |
| Map Gen      | Random Walk + grid-based algorithms |
| Architecture | Modular JS, entity-driven design    |
| Animations   | Timed cell flashes using Blessed    |

This mix is rare → and very impressive for a backend engineer.

---

# 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/rogue-dungeon.git
cd rogue-dungeon
npm install
npm start
```

---

# 🎮 Controls

| Action     | Keys                     |
| ---------- | ------------------------ |
| Move       | Arrow Keys / WASD / HJKL |
| Next Level | N                        |
| Restart    | R                        |
| Quit       | Q / Esc / Ctrl+C         |

---

# 🧠 What I Learned Building This

* Designing interactive CLI apps
* Building my own tiny “engine loop”
* Procedural generation
* Structuring a clean modular codebase
* Real-time rendering with Blessed
* Managing user input events and game timing
* Working with 2D grids, AI, and entity systems

These translate directly into backend + systems engineering skills.

---

# 🔮 Planned Upgrades

* Inventory & items (potions, weapons, armor)
* Fog of war (FOV shadow-casting)
* Boss floors
* More enemy types
* Talent system (perks on level-up)
* Save/load with JSON
* Mini-map
* Tile-based lighting
* More advanced animation effects (shake, glow, pulses)

---

# 🤝 Contribute / Fork It

This project is intentionally modular — easy to modify, extend, or fork.
Feel free to:

* Add monsters
* Add new dungeon generators
* Improve AI
* Add weapons or magic
* Create your own version

PRs are welcome!

---

# 📜 License

MIT — free for anyone to use or build upon.

---
