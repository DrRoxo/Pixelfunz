# Pixelfunz

⚔️ A D&D-style side-scrolling pixel art RPG contained in **a single file**: [`index.html`](index.html).

No build steps, no dependencies, no external assets — all pixel art is drawn procedurally on canvas. Just open `index.html` in a browser and play.

## How to play

1. Open `index.html` in any modern browser.
2. Press **Enter**, pick a class (Fighter, Rogue, Wizard, or Cleric), and roll your ability scores (4d6 drop lowest — press **R** to reroll).
3. Walk across the flat overworld, loot chests, and enter the cave entrances to descend into dungeon-crawler levels of rooms and corridors.
4. Slay the **Young Dragon** in Dungeon 3 to win!

Works on mobile too: on touch devices an on-screen D-pad and action buttons appear automatically.

## Controls

| Key | Action |
|---|---|
| ←/→ or A/D | Walk left/right (auto-steps up small ledges) |
| ↑ or W | Climb / hop up (needs ground underfoot or a wall to grab) |
| ↓ or S | Climb down |
| 1 | Attack |
| 2 | Cast spell (Wizard/Cleric) |
| 3 | Defend (+4 AC) |
| 4 | Flee |
| H | Drink a healing potion |
| P | Save game (while exploring) |
| L | Load saved game (also from title/game-over screens) |
| Enter | Confirm / start |

Gravity applies: walk off a ledge and you'll fall until you land. Water pools let you swim along at any depth.

On touch devices, an on-screen D-pad and buttons for all of the above are shown below the game canvas.

## D&D-style mechanics

- **d20 attack rolls** vs Armor Class, with ability modifiers and proficiency
- **Critical hits** on natural 20 (double damage dice), fumbles on natural 1
- **Initiative rolls** at the start of combat
- Class hit dice (d6–d10), weapon damage dice, sneak attack for Rogues, spell slots for casters
- Leveling with XP, hit-die HP gains, and full heals
- Rest at the town inn to restore HP, spells, and buy potions
