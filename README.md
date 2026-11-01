# Citadel: Six Months

A three-act, first-person prequel to *System Shock* (1994), built with three.js. It runs entirely in the browser.

**Play:** open the GitHub Pages link for this repository. The models load over the network, so the game won't run from a double-clicked `index.html`; it needs a web server (GitHub Pages, or `python -m http.server` locally).

**Controls:** WASD or arrow keys to move (Shift to run), mouse to look (click the view to capture it), E to use or talk, 1–3 to pick a reply, F or left-click to swing the pipe in Act 3. On phones there's an on-screen joystick with USE and HIT buttons.

## Credits

- 3D environment, props, drone and characters: [Quaternius](https://quaternius.com) (CC0): Modular Sci-Fi MegaKit, Sci-Fi Essentials Kit, Zombie Apocalypse Kit characters.
- Engine: [three.js](https://threejs.org) r128 (MIT), loaded from a CDN.
- Fonts: Chakra Petch and IBM Plex Mono from Google Fonts (SIL Open Font License).

*System Shock*, SHODAN, Citadel Station and TriOptimum belong to their rights holders (Nightdive Studios). This is a non-commercial fan project.

## Custom crew (Blender)
- `models/pia.json`, `models/lena.json`, `models/marcus.json` — Pia Varga, Lena Okafor and Marcus Hale (also used, tinted, for the Act 3 cyborg), each built in Blender with MPFB 2 (MakeHuman). MakeHuman base mesh and system assets are CC0. Animations retargeted from the Quaternius clips.
- `models/guard.json`, `models/diego.json`, `models/prisoner.json`, `models/mutanta.json`, `models/mutantb.json` — supporting cast and Act 3 mutants, same MPFB 2 / CC0 pipeline. The cartoon pack (`citadel-crew.json`) stays as a fallback.
