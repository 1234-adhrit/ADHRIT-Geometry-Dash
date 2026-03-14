# Neon Dash

A Geometry Dash inspired, single-file HTML5 runner with 5 distinct levels, animated hazards, and a neon sci‑fi interface.

## Features
- Five hand‑tuned levels with clear difficulty labels.
- Animated obstacles including pulsing spikes, floating blocks, and moving saws.
- Smooth canvas rendering with parallax stars and animated grid.
- Responsive layout that works on desktop and mobile.
- Simple Web Audio synth tones for jumps, crashes, and clears.

## How To Run
- Download or clone this repo.
- Open `index.html` in any modern browser.

No build tools or dependencies required.

## Controls
- Jump: `Space` or click/tap
- Restart: `R`
- Select level directly: `1` through `5`
- Cycle levels: `[` previous, `]` next

## Levels
1. Level 1: Neon Start (Easy)
2. Level 2: Pulse Streets (Normal)
3. Level 3: Rift Run (Hard)
4. Level 4: Chromatic Chaos (Insane)
5. Level 5: Apex Shift (Extreme)

Each level has its own speed, gravity, obstacle density, and theme colors.

## Gameplay Notes
- Hold your jump slightly longer for a higher arc.
- Levels 2–5 support a double jump.
- Audio starts only after the first click or key press due to browser autoplay rules.

## Customize
Open `index.html` and edit the `levels` array in the script section.
Suggested fields to tweak per level:
- `speed` (higher = faster scrolling)
- `gravity` (higher = heavier player)
- `jump` (higher = taller jump)
- `length` (distance required to clear the level)
- `density` (higher = more obstacles)
- `theme` colors

## Troubleshooting
- If the game looks blurry, ensure your browser zoom is at 100%.
- If audio is silent, click inside the canvas or press `Space` once to unlock audio.

## Credits
Created by you with help from Codex.

## Disclaimer
This is a fan‑made project inspired by Geometry Dash. It is not affiliated with or endorsed by the original creators.
