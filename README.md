# Farm Expedition RPG

A PVE Farm Village Simulator built with C++ and SFML.

---

## How to Run

### Requirements
- Docker installed and running

### (1) Pull the Docker image
```bash
docker pull --platform linux/amd64 chwoong/team_00_project:0.1.0
```

### (2) Run the game

**Option A — Run automatically:**
```bash
bash scripts/run.sh
```
Then open your browser and go to:
```
http://localhost:6080/vnc.html
```

**Option B — Enter the container first, then run manually:**
```bash
bash scripts/run_shell.sh
```
From inside the container:
```bash
./build/main
```
Then open: `http://localhost:6080/vnc.html`

---

## Game Introduction

Farm Expedition RPG is a day-based farm simulation game where you manage crops, livestock, and a village while defending against random disasters.

## Core Features

- **Agriculture** — Plant wheat, corn, and pumpkin. Raise cows and collect milk.
- **Construction** — Work construction, craft building materials, upgrade the village wall.
- **Marketplace** — Buy livestock and equipment. Sell crops and materials at fluctuating daily prices.
- **Stock Market** — Buy and sell stocks in 6 companies whose prices change every day.
- **Equipment** — Equip weapons and armor from your inventory.
- **Dungeon** — Enter the dungeon with your loadout and battle enemies.
- **Level System** — Gain EXP from farming and construction to level up your character.
- **Random Events** — Mad cow disease and zombie attacks occur randomly after day 3.
- **Stamina System** — Each action costs stamina. End the day to restore it.
