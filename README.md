# Sherwood Observatory Mission – play in your browser

**Play:** https://xao214.github.io/sherwood-mission/

A rogue A.I. has taken over the Sherwood Observatory. You have six hours to search its ten rooms for the nine fragments of the override password, then use the terminal in the Control Room before the A.I. moves the telescope and locks you out.

This is an original SNES homebrew game (a port of the C64 game *Sherwood Mission*), running in the browser with [EmulatorJS](https://emulatorjs.org) (snes9x core). It is made for an iPad in Safari, but works in any modern browser.

## On an iPad
1. Open the link above in Safari.
2. Tap **Share → Add to Home Screen**. Opened from the Home Screen it runs full screen, like an app.
3. Hold the iPad in landscape and tap **Tap to start**.
4. Use the on-screen D-pad and buttons. The **?** button (top left) shows the controls again and pauses the game. The ☰ button (top right) opens the emulator bar: pause, restart, save/load state, mute/volume and full screen.

## Controls

| Pad | Action |
|---|---|
| D-pad left / right | Run |
| UP (hold) | Search the furniture you are standing in front of (about 1.6 s). Also calls or rides a lift up. |
| DOWN | Call a lift, or ride one down |
| **B** (also Y or A) | Somersault jump |
| START | Start the game on the title screen; pause / resume |
| Main lift: UP / DOWN | Ride between the five levels |
| Main lift: LEFT / RIGHT | Enter the room on that side |
| Main lift: X or SELECT | Open the pocket computer (password and map). X, SELECT, B, A or START closes it. |

**Keyboard:** arrow keys, X = B, Z = A, S = Y, A = X, Enter = Start, V = Select. Bluetooth game controllers also work.

## How to play
* Search furniture (hold UP) to find the code letters. Each new game shuffles what the furniture holds: a code letter, a **robot freeze** (12 s), a **time bonus** (+10 min) or nothing.
* Touching a robot or a spark, or falling off the bottom of the screen, costs **10 minutes**.
* The clock starts at 6:00; one game minute is 4 seconds, so a full game is 24 minutes.
* When you have all 9 letters, search the Control Room terminal to win.

## Notes
* Save states (☰ → Save State / Load State) are kept in the browser on that device. The game itself has no save feature.
* iPad audio starts after the first tap. If you hear nothing, turn the volume up.

## Files
* `index.html` – the page and EmulatorJS settings (touch layout, hidden menus, tap-to-start).
* `rom/sherwood-mission-snes.sfc` – the game (512 KB LoROM, NTSC).
* `data/` – EmulatorJS 4.2.3 files (loader, emulator, snes9x core) copied from the EmulatorJS CDN, so the page doesn't depend on it.

EmulatorJS is GPL-3.0 (https://github.com/EmulatorJS/EmulatorJS). The snes9x core is under the snes9x licence (non-commercial use). The game is an original homebrew by Andy Outram.
