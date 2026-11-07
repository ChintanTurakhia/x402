# Kart Gauntlet

A 3D kart racer on a sky-high track with no guard rails. Race 5 rivals for 3 laps. If you die, you go back to the start of all 3 laps.

## Hazards
- **Cannon Alley**: cannons on both sides fire cannonballs across the track. A barrel glows red just before it fires. A hit knocks you off the track.
- **Spike Zigzag**: diagonal spike walls come in from alternating sides, so you have to weave through them. Touching a spike kills you.
- **Glove Gauntlet**: spring-loaded boxing gloves shake as they wind up, then punch across the track. Stay on the far side or time your pass.
- **The Void**: drive off the edge and you fall to your death.

Every death restarts the whole race: all 3 laps, the timer and the rivals.

## Controls
| Action | Keyboard | Touch |
| --- | --- | --- |
| Gas | ↑ / W | automatic |
| Brake / reverse | ↓ / S | BRAKE |
| Steer | ← → / A D | ◀ ▶ |
| Drift (hold while turning, release for a boost) | Space / Shift | DRIFT |
| Pause | P / Esc | II |
| Mute | M | |

Orange chevron pads give you a speed boost.

## Run it
The game is plain HTML plus a vendored copy of three.js (`vendor/`). Serve the folder with any static server:

```sh
python3 -m http.server 8000
# open http://localhost:8000
```
