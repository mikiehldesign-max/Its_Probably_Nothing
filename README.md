# It's Probably Nothing

> *"It wasn't."*

A cooperative story card game for 2–5 players. First to 5 trophies wins.

## How to Play

Flip an Encounter card and read it aloud. Every player must play one card from their hand — no passing. Cards are revealed simultaneously.

- **Highest scorer** = Spotlight winner → claims a trophy + success perk
- **Lowest scorer** = Weakest player → takes the failure penalty
- **First to 5 trophies** wins immediately

## Playing the Demo

Open `index.html` in any modern browser. No server needed.

## Adding Images

Drop illustration files into the `images/` folder and uncomment the matching lines in `index.html`.

### Encounter cards
- Folder: `images/encounters/`
- Size: **600 × 280px** landscape
- Format: JPG or PNG
- Filename: match the encounter ID exactly (e.g. `icecream2.jpg`, `mothman_enc.jpg`)

### Player cards
- Folder: `images/cards/[category]/`
- Size: **300 × 200px**
- Format: JPG or PNG
- Filename: match the card ID exactly (e.g. `rifle.jpg`, `veteran.jpg`)

## Card Count

| Category | Count |
|---|---|
| Encounter cards | 75 (70 regular + 5 boss) |
| Weapons | 14 |
| Artifacts | 14 |
| Tools | 14 |
| Instinct | 14 |
| Memory (2d6) | 14 |
| Interference | 14 |
| **Total player cards** | **84** |

## Folder Structure

```
its-probably-nothing/
├── index.html
├── README.md
└── images/
    ├── encounters/         ← 75 encounter illustrations (600×280px)
    └── cards/
        ├── weapons/        ← 14 cards
        ├── artifacts/      ← 14 cards
        ├── tools/          ← 14 cards
        ├── instinct/       ← 14 cards
        ├── memory/         ← 14 cards
        └── interference/   ← 14 cards
```
