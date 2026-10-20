# 🚌 Endless Bus Runner Game

An endless runner game featuring a city bus weaving through dynamic traffic, heavily inspired by *Temple Run* and *Subway Surfers*. 

**Designed and Created by:** Alex M.

---

## 🎮 Game Design Blueprint
* **The Player:** A city bus that constantly moves forward, accelerating gradually over time.
* **The Track:** A 3-lane highway (Left, Center, Right).
* **The Obstacles (Traffic):** Commuter cars, roadblocks, construction cones, and broken-down trucks blocking specific lanes.
* **Controls:** `Left Arrow` / `A` to switch left, `Right Arrow` / `D` to switch right.

---

## 🛠️ Built With
* **Engine:** [Godot Engine 4](https://godotengine.org/) (100% Free and Open Source)
* **Language:** GDScript

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### 2. Import into Godot
1. Download and open **Godot Engine 4**.
2. Click **Import** in the Project Manager.
3. Browse to this folder and select the `project.godot` file.
4. Click **Import & Edit**.

---

## 🗂️ Project Repository Architecture
* `project.godot` - Core engine project configuration index file.
* `bus_player.gd` - Standard controller script handling bus movement, lane shifts, and crashes.
* `road_spawner.gd` - Logic handler for dynamically spawning endless segments of highway ahead of the player.
* `.gitignore` - Excludes engine cache, imports, and temporary system data from Git tracking.
