# D.A.D.

An adaptive maths game for children with 1980s Amstrad CPC–style graphics.

🎮 **Play it live:** https://imran2akram.github.io/maths-diver/

## How to play

Open `index.html` in any modern browser — no build step, no dependencies.

1. **Enter your age** (4–18) and press **OK** to start at the right difficulty.
2. **Answer the maths question** shown on screen.
   - Correct → your character climbs **up** one rung of the ladder.
   - Wrong → character falls **down** one rung (the correct answer is shown briefly).
3. **Reach the top rung** → character runs across the diving board, jumps off, and **parachutes** down into the pool. 🎉
4. A new level begins with harder questions.

## Features

| Feature | Detail |
|---|---|
| Adaptive difficulty | Tracks a hidden skill score; questions get harder as you improve, easier if you struggle |
| Age-based starting point | Age 4–6 → simple addition; age 12+ → full times-tables & division |
| Amstrad CPC visuals | 320×200 virtual canvas, blocky pixel-art characters, CPC colour palette |
| 8-bit audio | Square-wave beeps via Web Audio API |
| Touch friendly | On-screen numpad works on any phone or tablet |
| Keyboard friendly | Type numbers and press Enter on desktop |

## Controls

Only two input actions are ever needed:
- **Entering your age** at the start screen
- **Entering an answer** during gameplay

Both the keyboard and the on-screen numpad work at all times.