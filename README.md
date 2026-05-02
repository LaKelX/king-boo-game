# 👑 KING BOO · Royal Haunting

A single-file Three.js game where **you play as King Boo** floating through a haunted mansion, scaring Marios and Luigis with your royal tongue lash.

> *The crown is yours. The mansion is theirs. Take both.*

## Play

**[▶ Play in browser (htmlpreview)](https://htmlpreview.github.io/?https://github.com/LaKelX/king-boo-game/blob/main/index.html)**

Or download `index.html` and open in Chrome.

## Controls

| Key | Action |
|---|---|
| **WASD** | Float around the mansion |
| **Mouse** | Rotate the royal gaze |
| **SPACE** | Tongue lash · scare Marios |
| **E** | Vanish (sneak past plumbers) |
| **SHIFT** | Royal dash |

## Goal

Capture all 8 Marios with your tongue. They flee when they see you — so use **vanish** to sneak up on them, then lash with **SPACE** for the catch.

- **+5 points** when a Mario / Luigi is scared by sight
- **+100 points** when captured (becomes a ghost)

## Tech

- Pure Three.js (via importmap CDN — no build step)
- Single HTML file
- Custom King Boo character built from primitives (sphere body, animated tongue, gold crown with gems, trailing wisps)
- Mario / Luigi NPCs with wander AI + scared AI + flee behavior + speech bubbles
- Haunted mansion: jack-o-lanterns with flickering point lights, columns, checkered floor, purple fog

## Built by

A Eudaimon creation · 2026
