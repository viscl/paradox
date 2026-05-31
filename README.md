# Paradox — A Probability Sandbox

An interactive playground for the most counterintuitive ideas in probability. Run the experiments yourself, watch the simulations converge on the theory in real time, and make predictions before the math reveals itself.

Built as a single self-contained HTML file — no build step, no dependencies, no server. Open it and it works.

**[▶ Live demo](https://viscl.github.io/paradox/)**

---

## What's inside

Seven experiments across three chambers, each computing its answer live from theory rather than hard-coded numbers:

**I · Simulation Arena (Frequentist)**
- **Birthday Problem** — In a room of *n* people, how likely is a shared birthday? Run rooms over and over and watch the rate climb past 50% at just 23 people.
- **Monty Hall** — The door, the host, and the switch. Crank up the door count to feel why switching wins.
- **Gambler's Ruin** — Bet one chip per round until you own everything or nothing. A tiny house edge bends the random walk toward ruin.

**II · Bayesian Studio**
- **Medical Testing** — Ten thousand people, a rare disease, a near-perfect test. Watch the base-rate trap: a positive result can still mean you're probably fine.
- **Coin Bias Inference** — Flip a coin of unknown bias and watch the Bayesian posterior tighten around the truth.

**III · Paradox Hall**
- **Simpson's Paradox** — A trend that reverses when you combine the groups.
- **St. Petersburg Paradox** — A game with infinite expected value that no one would pay much to play.

## Features

- **Live convergence graphs** — watch experimental results race toward the theoretical value.
- **Challenge mode** — predict the outcome, lock in your guess, then watch the simulation prove (or disprove) you. Scores and badges are saved locally.
- **Plain English mode** — swap the formulas for word explanations.
- **Lab write-ups** — generate a Markdown summary of any experiment to copy or download.
- **Light & dark themes** — a warm light mode and a focused dark mode, with your choice remembered.
- **Keyboard shortcuts** — press `?` to see them.
- **Accessible** — screen-reader announcements for live stats, focus-managed dialogs, and reduced-motion support.

## Running it

**Online:** just visit the live demo link above.

**Locally:** download `index.html` and open it in any modern browser. That's the whole process — there is nothing to install.

## Tech

Vanilla JavaScript and the HTML5 Canvas 2D API. No frameworks, no libraries, no build tooling. The entire app — markup, styles, logic, and seven experiments — lives in one file by design, so it stays portable and trivial to host or share.

## License

MIT — see [LICENSE](LICENSE). Free to use, modify, and share.

## Acknowledgements

Fonts: [Source Serif 4](https://fonts.google.com/specimen/Source+Serif+4), [Hanken Grotesk](https://fonts.google.com/specimen/Hanken+Grotesk), and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono), all via Google Fonts.
