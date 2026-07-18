# Level Up

A layered browser incremental game where every click earns XP. Level 1 begins at exactly **5 XP**, and every following level costs approximately **100,000× more XP**.

## Progression

- Level 1: Manual XP training
- Level 3: Energy — manually channel it, automate it, and boost XP
- Level 8: Knowledge — convert Energy and improve every lower resource
- Level 15: Crystals — reset a run for permanent Crystal upgrades
- Level 25: Essence — collapse lower layers for rule-changing upgrades

Each currency has its own collection method, generators, and upgrades. Higher currencies multiply the production of lower layers. The game also includes ranks, statistics, offline progress, automatic saving, and save export/import.

Every level from 1 through 30 unlocks new content. Leveling itself does not increase XP production. Players must purchase Training upgrades and develop Energy, Knowledge, Crystal, and Essence mechanics to overcome each 100,000× requirement jump.

Level 2 immediately unlocks a free, one-time 1,000× XP Overclock for the current run. Training Upgrades are displayed directly below the XP button so the route to the next level is always visible.

## Run

Open `index.html`, or run a static server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Galaxy.click

Upload a ZIP containing `index.html`, `styles.css`, `layers.css`, `level-content.css`, and `game.js`. Use `index.html` as the entry point.

## License

MIT
