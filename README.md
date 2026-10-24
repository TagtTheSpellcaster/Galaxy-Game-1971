# Galaxy Game (1971) - Arcade Recreation

![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC.svg)
![Web Audio API](https://img.shields.io/badge/Audio-Web_Audio_API-green.svg)
![Status](https://img.shields.io/badge/Status-Playable-brightgreen.svg)

A faithful single-file HTML5/JavaScript recreation of **Galaxy Game (1971)**, widely recognized as the world's first commercial coin-operated arcade game created by Bill Pitts and Hugh Tuck at Stanford University.

**Play directly in your browser:** [https://tagtthespellcaster.github.io/Galaxy-Game-1971/](https://tagtthespellcaster.github.io/Galaxy-Game-1971/)

## Features

- **Phosphor CRT Aesthetics:** Simulated vector monitor line art, starfield background, motion trails, and scanline overlays.
- **Authentic Newtonian Physics:** Real gravitational mechanics pulled toward a central star with screen wrap-around.
- **1-Player vs AI & 2-Player Local Dual Modes:** Challenge an adaptive AI featuring deflection shooting, bullet evasion, and orbital navigation, or fight a friend locally.
- **Ship Selection:** Play as **The Wedge** or **The Needle**.
- **Retro Synthesizer Sound:** Built-in procedural Web Audio API synthesizers for thrusters, square-wave missiles, coin drops, and explosions.
- **Coin-Op System & Pause Feature:** Simulates inserting coins (`C`) to buy credits and pausing at any time (`ESC`).

## Controls & Instructions

### General Controls
- **Insert Coin / Credit:** Press `C` (or click the **INSERT COIN** button)
- **Start 1-Player vs AI:** Press `1`
- **Start 2-Player Local:** Press `2`
- **Pause / Unpause:** Press `ESC`

### Single Player Mode Controls
In **1-Player Mode**, all key mappings are active for seamless control:

| Action | Primary Keys | Alternative Keys |
| :--- | :---: | :---: |
| **Rotate Left** | `A` | `←` (Left Arrow) |
| **Rotate Right** | `D` | `→` (Right Arrow) |
| **Thrust** | `W` | `↑` (Up Arrow) |
| **Fire Torpedo** | `S` | `Spacebar` / `Right Shift` |
| **Hyperspace Jump** | `Left Shift` | `Control` (`Ctrl`) |

### Two-Player Local Controls

#### Player 1 (Left / The Wedge)
- **Rotate Left / Right:** `A` / `D`
- **Thrust:** `W`
- **Fire Torpedo:** `S`
- **Hyperspace:** `Left Shift`

#### 🔵 Player 2 (Right / The Needle)
- **Rotate Left / Right:** `←` / `→` (Arrow Keys)
- **Thrust:** `↑` (Up Arrow)
- **Fire Torpedo:** `↓` (Down Arrow)
- **Hyperspace:** `Spacebar` or `Enter`

## How to Play

1. **Insert a Coin:** Press `C` or click the yellow button to add credits.
2. **Select Mode & Ship:** In 1P mode, pick whether you want to control **The Wedge** or **The Needle**.
3. **Avoid the Sun:** The central star pulls both ships in. Get too close, and gravity will destroy your ship!
4. **Master Inertia:** Thrusting builds linear momentum while rotating changes your orientation.
5. **Use Hyperspace Wisely:** Entering Hyperspace teleports your ship to a random position on the screen, but each consecutive attempt increases the risk of ship explosion!

## Local Development

Because this project is built as a single zero-dependency HTML file, no installation or build steps are required.

1. Clone this repository:
   ```bash
   git clone https://github.com/tagtthespellcaster/Galaxy-Game-1971.git
   ```
2. Open `index.html` (or `galaxy_game_1971.html`) directly in any modern web browser.

## License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**. See the `LICENSE` file for details.