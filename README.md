# Drill Survivor

A browser-based survival game inspired by Vampire Survivors, built with vanilla JavaScript, HTML, and SVG graphics. No dependencies, no build step — just open and play.

## Play Now

**[Play Drill Survivor](https://kr1s-z.github.io/game/)**

## About

You are an oil rig fighting through waves of eco activists, bureaucrats, and politicians. Move to survive. Drill enemies on contact. Collect certificates and weapons to power up.

### Controls

| Key | Action |
|-----|--------|
| `W` / `Arrow Up` | Move up |
| `S` / `Arrow Down` | Move down |
| `A` / `Arrow Left` | Move left |
| `D` / `Arrow Right` | Move right |

No shooting button needed — weapons auto-fire!

### Levels

| Level | Theme | Enemies | Boss |
|-------|-------|---------|------|
| 1 | Eco Storm | Protestors with signs | Eco Alliance Leader (giant tree) |
| 2 | Red Tape | Flying folder drones | Mega Bank Vault (armored safe) |
| 3 | Capitol Hill | Government officials | Slick Senator (politician) |

### Weapons

Weapons spawn as pickups and fire automatically. Collecting duplicates upgrades them.

| Weapon | Effect | Upgrade |
|--------|--------|---------|
| Drill Shot | Fires drill bits at nearest enemy | More projectiles, faster fire rate |
| Oil Spray | Damages all enemies in a ring around you | Bigger radius, more damage |
| Pipe Wrench | Orbits around you, hitting enemies | Extra wrenches, wider orbit |

### Mechanics

- **Boss every 500 points** — each level's boss appears when you hit the score threshold
- **Certificates** — collect for points and random upgrades (+HP, +Speed, +Damage, +Max HP)
- **Boss square attack** — bosses summon a square formation of enemies around you
- **High scores** — saved locally in your browser via localStorage
- **Beat all 3 bosses** to win and earn the right to build your own oil rig!

## Tech Stack

- Single `index.html` file (~1400 lines)
- Vanilla JavaScript (no frameworks, no dependencies)
- SVG for all graphics (no Canvas, no images)
- CSS for UI overlays
- `requestAnimationFrame` game loop
- `localStorage` for high score persistence

## Run Locally

Just open the file:

```bash
open index.html
```

Or serve it:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## License

Open source. Do whatever you want with it.
