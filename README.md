# Silicon Dreams

**Build a CPU from scratch** — an interactive, gamified journey from transistors to computing.

![Level Preview](https://img.shields.io/badge/Levels-10-00f5ff) ![No Dependencies](https://img.shields.io/badge/Dependencies-None-00ff88) ![Single File](https://img.shields.io/badge/Size-Single%20HTML-ff00aa)

## What is this?

Silicon Dreams is a browser-based puzzle game that teaches digital logic by having you *actually build* circuits. Start with individual NMOS and PMOS transistors, wire them together to create logic gates, then combine those gates to build real computing hardware.

**No prior knowledge required** — the game teaches you as you go.

## Play Now

Open `index.html` in your browser. That's it. No build step, no dependencies, no server required.

Or play the hosted version: [geniusyinka.github.io/silicon-dreams](https://geniusyinka.github.io/silicon-dreams/)

## Levels

| # | Level | What You'll Build |
|---|-------|-------------------|
| 1 | The Transistor | Learn how NMOS switches work |
| 2 | NOT Gate (Inverter) | PMOS + NMOS = your first gate |
| 3 | Buffer | Two NOTs make a right |
| 4 | NAND Gate | The universal gate — build anything from this |
| 5 | AND Gate | NAND + NOT |
| 6 | OR Gate | Built purely from NANDs |
| 7 | XOR Gate | The key to arithmetic |
| 8 | Half Adder | Your first computing circuit! |
| 9 | 2:1 Multiplexer | Data routing fundamentals |
| 10 | SR Latch | Memory! Sequential logic begins |

## Features

- **Drag & drop** transistors, gates, and wires onto the canvas
- **Real-time simulation** with electron flow animations
- **Truth table verification** — see your circuit tested against all inputs
- **Progressive unlocking** — build gates from transistors, then use them as building blocks
- **Achievement system** with 12 badges to unlock
- **Procedural synth SFX** — satisfying retro-futuristic audio feedback
- **Keyboard shortcuts** — V (select), W (wire), X (delete)

## Why?

Understanding how computers work at the transistor level is mind-blowing. A CPU is just billions of tiny switches, arranged cleverly. This game makes that tangible.

Inspired by [Nand2Tetris](https://www.nand2tetris.org/) and [Turing Complete](https://store.steampowered.com/app/1444480/Turing_Complete/), but focused on the transistor-to-gate journey with immediate visual feedback.

## Tech

- Single HTML file (~2700 lines)
- Vanilla JavaScript, no frameworks
- HTML5 Canvas for rendering
- Web Audio API for procedural sound synthesis
- Zero dependencies

## Controls

| Action | Mouse | Keyboard |
|--------|-------|----------|
| Select/Toggle | Click component | V |
| Draw Wire | Click pin to pin | W |
| Delete | Click with delete tool | X / Delete / Backspace |
| Run Tests | Click RUN button | — |

## License

MIT — do whatever you want with it.

## Contributing

PRs welcome. Some ideas:
- More levels (Full Adder, ALU, registers, simple CPU)
- Sandbox/freeplay mode
- Save/load circuits
- Mobile touch support
- Accessibility improvements
