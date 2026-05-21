# STAR WARS: SWARMS

Browser-based 2D space shooter. You pilot a ship, fend off swarms of TIE
fighter enemies, collect R2-D2 droids for points, and grab ammo supply drops
to keep firing.

Single-file game: all HTML, CSS, and JavaScript live in `test.html`. No build
step, no dependencies — open the file in a browser and play.

## Controls

| Action | Keys |
|---|---|
| Move | `WASD` or arrow keys |
| Shoot | `Space` |
| Aim line | Hold left mouse button |

## Gameplay

- **Player ship** (`6.png`) — moves around the screen, shoots in its facing direction.
- **TIE fighter enemies** (`tie7.png`) — spawn and chase / attack the player.
- **R2-D2 pickups** (`R2-D2-PNG-Clipart.png`) — collect to score points (top-right counter: *"R2D2's collected"*).
- **Ammo supply drops** (`ammo2.png`) — refill bullets (counter format: `Bullets: 30 / 60`).
- **Game Over** — when you die you can restart immediately or go back to the main menu.

## Menus

- **Start menu** — Start Game / View Controls.
- **Controls menu** — visual reference for the WASD/arrows/space/click bindings.
- **Game over overlay** — Restart or Menu.

## Files

```
test.html                       Whole game (HTML + CSS + JS)
bak2.jpeg                       Space background
6.png                           Player ship sprite
tie7.png                        TIE fighter enemy sprite
R2-D2-PNG-Clipart.png           Points pickup sprite
ammo2.png                       Ammo supply drop sprite
wasd.png, arrows.png            Movement key indicators (controls menu)
space.png, klik.png             Shoot / aim key indicators (controls menu)
```

## Running

Open `test.html` in any modern browser. Or serve the folder with any static
server (e.g. `python -m http.server`) and visit `http://localhost:8000/test.html`.

## Note

The HTML file is named `test.html` for historical reasons — if you want a
nicer URL, rename it to `index.html`. Browsers will then load it automatically
when you point them at the folder.
