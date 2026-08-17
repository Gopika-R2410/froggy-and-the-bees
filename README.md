<div align="center">

# CUTE FROG POND ADVENTURE

**A minimalist arcade experience built for the browser.**

<br>

![Status](https://img.shields.io/badge/STATUS-ACTIVE-2E8B57?style=for-the-badge&labelColor=1a1a1a)
![Build](https://img.shields.io/badge/DEPENDENCIES-ZERO-DAA520?style=for-the-badge&labelColor=1a1a1a)
![Stack](https://img.shields.io/badge/STACK-HTML5%20%C2%B7%20CSS3%20%C2%B7%20JS-FFD700?style=for-the-badge&labelColor=1a1a1a)
![Platform](https://img.shields.io/badge/PLATFORM-WEB%20%C2%B7%20MOBILE-228B22?style=for-the-badge&labelColor=1a1a1a)

<br>

</div>

---

## Overview

Cute Frog Pond Adventure is a single-file, dependency-free arcade game rendered entirely on HTML5 Canvas. Control a frog navigating a lily pond, strike incoming flies with a tongue mechanic, and race against a sixty-second timer while managing a limited health pool. Every visual, sound, and interaction is generated natively in the browser — no images, no audio files, no external libraries.

---

## Core Mechanics

<table>
<tr>
<td width="33%" valign="top">

### Movement
Directional control via keyboard or touch drag, with idle detection that penalizes prolonged inactivity.

</td>
<td width="33%" valign="top">

### Targeting
A tongue-strike mechanic driven by cursor position, spacebar, or a single tap on mobile.

</td>
<td width="33%" valign="top">

### Progression
Five escalating difficulty tiers compressed into a single sixty-second session.

</td>
</tr>
</table>

---

## Feature Set

| Category | Detail |
|---|---|
| Tongue-Strike Mechanic | Precision targeting via mouse, keyboard, or touch |
| Fly Variants | Standard, high-value bonus, and hazard types |
| Combo System | Multiplier scaling up to eight times base score |
| Difficulty Curve | Five levels of escalating spawn rate and speed |
| Visual Feedback | Particle bursts, glow effects, screen shake |
| Audio Engine | Real-time synthesized sound via Web Audio API |
| Leaderboard | Session-based top ten with rank and timestamp |
| Cross-Platform Input | Full parity between desktop and touch controls |
| Pause State | Instant pause and resume on demand |

---

## Controls

<div align="center">

| Action | Desktop | Mobile |
|:---:|:---:|:---:|
| Move | `W` `A` `S` `D` or Arrow Keys | Drag |
| Strike | `Space` or Click | Tap |
| Pause | `P` | — |

</div>

---

## Scoring Reference

| Event | Result |
|---|---|
| Standard fly caught | Plus ten points |
| Bonus fly caught | Plus thirty points |
| Hazard fly caught | Minus one health, combo reset |
| Idle beyond five seconds | Minus one health |
| Fly escapes uncaught | Minus one health |
| Health reaches zero | Session ends |

Consecutive successful catches build a multiplier. Any miss, hazard contact, or idle penalty resets it to baseline.

---

## Setup
<div align="center">
No build process. No installation. No server dependency.
Save the file as index.html
Open directly in any modern browser
Begin play immediately
</div>

---

Optional local hosting:

```bash
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000/index.html`

---

## Technical Composition

<div align="center">

| Layer | Technology |
|---|---|
| Rendering | HTML5 Canvas API |
| Logic | Vanilla JavaScript, ES6+ |
| Audio | Web Audio API, procedural synthesis |
| Styling | CSS3, gradients and transitions |

</div>

---

## Architecture

index.html
├── Markup — layout and structure
├── Styles — theming, animation, responsive rules
└── Script — game state, rendering loop, input handling

A single-file architecture with no external dependencies, no bundler, and no runtime requirements beyond a browser.

---

## Roadmap

- Additional environment themes beyond the default pond
- Temporary power-up system
- Persistent score storage across sessions
- Selectable difficulty presets
- Optional networked leaderboard

---

## Contributing

Contributions are welcome through standard fork and pull request workflow. Bug reports, performance improvements, and feature proposals are all in scope.

---

## License

Free for personal, educational, and non-commercial use. Modification and redistribution permitted with attribution.

---

<div align="center">

**CUTE FROG POND ADVENTURE**

*Built in a single file. Designed to be played immediately.*

</div>
