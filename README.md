# Robo Beat

A simple drum machine with synthesized 80s sounds, inspired by Roland's "Human Rhythm Composer" series (R-5/R-8). Companion to ROBO/SOLO for Robo Galaktika. Runs in a phone browser, no app store install needed.

## Features

- **16-step grid, 8 instruments**: kick, snare, clap, hat, open hat, tom hi, tom lo, cowbell. All sounds are synthesized (808 and Simmons style).
- **Tap a cell**: off → hit → accent → off.
- **Patterns A and B**: switch at the end of the bar, so they never land off-beat. **FILL** plays one bar, then returns.
- **HUMAN**: small variations in timing and dynamics so the beat isn't stiff, an idea taken from the R-5.
- **Swing**, **tempo** with tap tempo, and per-instrument **mute** (tap the instrument name).
- **Big pads** for live playing.
- **7 preset patterns**: Synth Pop, New Wave, 80s Disco, Electro 808, 80s Simmons, Ballad, Empty.
- **Auto-save** on the device, with an Undo button when loading a pattern or clearing a section.
- **Keyboard**: space to play/stop.

## Put it online with GitHub Pages

1. Create a new GitHub repo, e.g. `robo-beat`.
2. Upload all files in this folder (**Add file → Upload files**).
3. Open **Settings → Pages**, set *Source* to **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. Wait 1–2 minutes. The app will be at `https://<username>.github.io/robo-beat/`.

## Install on your phone

Open that address in Chrome or Safari and choose **Add to Home Screen**.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app |
| `manifest.webmanifest` | Data for "Add to Home Screen" |
| `icon-192.png`, `icon-512.png` | App icons |
| `.nojekyll` | Makes GitHub Pages serve the files as they are |
