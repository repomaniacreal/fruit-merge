# 🍉 Fruit Merge

A juicy single-file HTML5 merge-puzzle game. Drop fruits, merge matching pairs, and work your way up to the legendary WATERMELON!

## How to Play

- **Drag** on the box to aim, **release** to drop the current fruit
- Two **same fruits** that touch **merge** into the next bigger fruit
- Merge chain: 🍒 Cherry → 🍓 Strawberry → 🍇 Grape → 🍊 Orange → 🍎 Apple → 🍐 Pear → 🍑 Peach → 🍍 Pineapple → 🍈 Melon → 🍉 **WATERMELON**
- Quick consecutive merges build a **⛓️ CHAIN combo** for multiplied points
- Two watermelons colliding vanish in glory for a **+2500 DOUBLE MELON** bonus
- **Game Over** if the fruit pile crosses the red danger line for too long

## Features

- Soft-body-ish circle physics with impulse-based collisions
- Merge bursts, shockwave rings, confetti, floating score popups, and screen shake
- Juicy synthesized sound effects (Web Audio API) that rise in pitch with fruit tier
- Live **NEXT fruit** preview and combo chain HUD
- Persistent best score and watermelon count (localStorage)

## Controls

| Input | Action |
|---|---|
| Drag (mouse / touch) | Aim the dropper |
| Release | Drop the fruit |

## Run It

Just open `index.html` in any modern browser — no build step, no dependencies, no server required. Works with both mouse and touch.

## Tech

- Single HTML file, vanilla JavaScript + Canvas 2D
- Custom circle-collision physics engine with substepped integration
- Web Audio API for all sound effects
