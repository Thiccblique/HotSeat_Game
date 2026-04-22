# Hot Seat

A party game for groups. Players take turns in the "hot seat" — spin to pick a player, spin to pick a challenge, and vote on whether they pulled it off.

---

## How to Play

1. Open `HotSeat.html` in any modern browser (no server required).
2. On the **Setup** screen, add at least 2 players and at least 1 challenge.
3. Configure your options (rounds, timer, wildcards), then click **Start Game**.
4. **Spin the name wheel** to pick who's in the hot seat.
5. **Spin the challenge wheel** to pick their challenge.
6. Review the result, then click **Start Challenge**.
7. A countdown timer runs (if enabled). When time is up — or you click Done — vote on whether the player completed it.
8. The leaderboard shows scores after every round. Keep going until all rounds are done.

---

## Setup Options

| Option | Choices | Default |
|---|---|---|
| Rounds | 5 / 10 / 15 | 10 |
| Timer | Off / 30s / 60s / 90s | 30s |
| Wildcard challenges | On / Off | On |
| No duplicate challenges | On / Off | Off |

---

## Features

- **Spin wheels** — Two physics-based wheels with tick sounds and stopper pegs. Swipe on the wheel canvas to spin (speed > 200 px/s triggers it).
- **Player colors** — Each player is assigned a color from the palette. Their color appears on their name tag and on the name wheel segments.
- **Wildcard** — When enabled, two WILDCARD slots are added to the challenge wheel. Landing on one picks a random challenge from the built-in suggestion library.
- **Skip token** — Each player gets one skip per game. Use it on the result screen to re-spin the challenge wheel.
- **Challenge timer** — A circular SVG countdown arc counts down from the configured duration. The digit turns pink under 10 seconds with a beep each second.
- **Vote screen** — After the timer, players vote YES (+1 point) or NOPE. Points are tracked per player across rounds.
- **Leaderboard** — Sorted after every round with player colors and scores. Next Round continues; End Game resets to setup.
- **Round counter** — Fixed top-left display shows current round and total.
- **Fullscreen** — Top-right button toggles fullscreen mode.
- **Ambient music** — Three low-frequency sine tones start when the game begins and run in the background.

---

## Built-in Challenge Categories

Funny · Physical · Brain · Perform · Social · Faith

Browse and add suggestions from the challenge panel on the setup screen.

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Esc` on Setup | Leave game prompt |
| `Esc` on Game | Back to Setup |
| `Esc` on Challenge | Cancel spin, back to Game |
| `Esc` on Result | Back to Game |
| `Esc` on Timer | Stop timer, back to Result |
| `Esc` on Vote | Back to Result |

---

## Requirements

- Any modern browser with Web Audio API support (Chrome, Firefox, Edge, Safari).
- No installation, no server, no dependencies — just open the HTML file.

---

*A Hope Studios / Marcos Hope Production*
