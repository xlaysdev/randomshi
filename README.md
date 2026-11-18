# FUNKY LAB — Tweenslop Editor

A mobile-friendly, single-file browser editor for making chaotic composited edits and “funkifying” media.

## Features

- Import multiple images and video clips as separate layers.
- Add editable text/captions with fill and outline colors.
- Layer selection, visibility, ordering, opacity, position, scale, rotation and blend modes.
- Background scenes: Void, Windows XP-style hill, Arcade, Space and Inferno; or upload your own background image.
- Motion presets per layer: Still, Bounce, Slam, Float, Dance, Shake and Pulse.
- Global effects: neon glow, echo/afterimages, RGB split, impact shake, scanlines, beat flashes and hue shift.
- 12-second looping preview with seek bar and WebM recording/export.
- Responsive layout for phones and desktop. No build tools or external libraries.

## Use

Open `index.html` in a modern browser. Upload images/videos, add text, choose a background, select a layer and tune its motion/effects. Transparent PNG cutouts work especially well.

## Export

Press **Export video** to record a 12-second WebM loop. Browser support for MediaRecorder/WebM is required; Chrome on Android or desktop is recommended.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.

Live URL: https://xlaysdev.github.io/randomshi/

## Notes

Project export currently saves the composition settings as JSON; imported media files are not embedded in that JSON. Keep the original media files available if you want to rebuild the project later.
