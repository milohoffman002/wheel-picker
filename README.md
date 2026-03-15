# Wheel Picker 🎡

A fun, interactive spinning wheel for randomly selecting from a list of names or items. Perfect for meetings, giveaways, or decisions! Built for screen sharing with dramatic visuals and sound.

## Spin Now

Open [`index.html`](https://milohoffman002.github.io/wheel-picker/) in your browser to start spinning and picking!

## Features

- **Add items easily** — Paste a list or enter one at a time
- **Colorful wheel** — Vibrant segments with crisp Canvas rendering
- **Readable text** — Dynamic font sizing based on number of items (14px to 28px)
- **Dramatic spin physics** — Starts fast, smoothly decelerates for suspense
- **Clicking sounds** — Audible ticks as segments pass the pointer
- **Victory celebration** — Fanfare music + confetti + animated winner reveal
- **Full screen mode** — Perfect for screen sharing (hides controls, shows only wheel + winner)
- **Sound toggle** — Enable/disable all audio
- **Manage items** — Remove individual items or clear all
- **Shuffle colors** — Randomize segment colors anytime
- **Dark theme** — Easy on the eyes
- **🆕 Tournament Mode (Elimination)** — Spin to eliminate items one by one until a final winner remains

## How to Use

### Normal Mode (Random Winner)
1. Open `index.html` in any modern browser
2. Enter names/items in the text area (one per line)
3. Click **Add to Wheel**
4. (Optional) Click **⛶ Full Screen** for screen sharing mode
5. Click **Spin the Wheel** and enjoy the show!
6. The winner is celebrated with music, confetti, and animation

### Tournament Mode (Elimination)
1. Switch to **Elimination** mode using the game mode toggle
2. Click **Start Elimination Round** to lock in your items
3. Click **Spin the Wheel** — the picked item is eliminated (removed from wheel)
4. Continue spinning until only 2 items remain
5. The final spin eliminates one item — the remaining item is the **WINNER**!
6. Watch the special winner overlay celebration
7. Click **🔄 Reset Elimination** to start a new round with the same items

**Tournament Mode Features:**
- Track eliminated items in a greyed-out "Eliminated" section
- See round progress (e.g., "Round 3 of 5")
- Strikethrough styling on eliminated items
- Dramatic winner reveal when tournament completes

**Elimination Mode Configuration:**

- **Opening String** — Optional text shown in the winner display at the start of each spin (e.g. *"Spinning for…"*). Leave blank to show nothing until a result comes in.
- **Elimination Message** — Appended to the winner display after each elimination (e.g. *"Pizza eliminated!"*). Defaults to `eliminated`.
- **Slice Animation** — When enabled, the selected slice expands with a gold glow and pulses for 1.5 seconds before flying off the wheel, making it easy to see which item was picked. Disable for instant eliminations. Only visible when Elimination mode is active.

## Use Cases

- Meeting facilitation (who goes first?)
- Giveaway winner selection
- Random decision making
- Team assignments
- Party games
- Live streaming / content creation
- **Tournament brackets** — Elimination mode for running brackets round by round
- **March Madness style** — Narrow down options until a champion emerges
- **Team drafts** — Elimination format for fair pick ordering

## Tech Stack

- HTML5 Canvas for high-performance wheel rendering
- CSS3 animations and gradients
- Vanilla JavaScript
- Web Audio API for generated sounds (no external audio files)
- Canvas-based confetti particle system

## Keyboard Shortcuts

- Click **⛶ Full Screen** button to enter presentation mode
- Click **✕ Exit Full Screen** or press Escape to return to normal view

## License

MIT License
