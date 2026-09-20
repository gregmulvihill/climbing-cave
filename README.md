# Climbing Cave

Interactive 3D design tool for a home climbing cave: a half-torus arch carved as a void
from a 20 x 20 x 12 ft room.

The viewer is a single self-contained `index.html` using three.js r128 from CDN.

## Features

- Adjustable hole diameter and ceiling height
- 4x4 and 8x4 plywood panel layout with cut lists
- Frame visualization
- Per-panel clickable volumes (pyramids and truncated pyramids) with individual editing
- Shape catalogue with dimensioned drawings and angles
- Hold placement (jug, sloper, crimp, pinch)
- Save / share configs, encoded as URL-safe base64 in the URL hash (`#cfg=...`)

## Usage

Open `index.html` in a browser. No build step, no dependencies to install.

## Controls

Q / Z adjust the active parameter. Click a panel to edit its volumes.
