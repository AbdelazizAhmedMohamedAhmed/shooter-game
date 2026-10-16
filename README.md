# Neon Siege

A browser shooter game built with HTML Canvas, CSS, and JavaScript. No dependencies or build step.

## Play

Download or clone this repository, then open `index.html` in a modern browser.

Optionally serve the project locally:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000.

## Controls

- WASD or arrow keys: move
- Mouse: aim
- Hold click or Space: shoot
- P: pause or resume
- Touch: use the movement arrows and hold the arena to aim and fire

Survive waves of enemies. Each cleared wave restores 10 health. Larger enemies appear from wave 3. Your best score is saved locally when browser storage is available.

## Structure

`index.html` contains the interface, styles, and game loop. All visuals are drawn procedurally, with no external assets.

## Next build ideas

Weapon upgrades, boss waves, sound effects, and new maps.

## Validation

Files saved and checked through GitHub. Browser gameplay testing is pending because the cloud workspace was still starting.
