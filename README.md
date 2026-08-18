# Isaac Moriah Codex Pet

Isaac Moriah is a custom animated pet for Codex, built from pixel-art sprite assets inspired by *The Binding of Isaac: Rebirth*.

## Contents

- `pet.json` - Codex pet manifest.
- `spritesheet.webp` - Animated pet spritesheet used by Codex.

## Notes

This pet was made using sprites taken from *The Binding of Isaac: Rebirth* as source material.

Some animation frames were also created by splitting well-known Isaac GIF files into individual frames and adapting them for the Codex pet spritesheet.

## Current Animation Setup

The current spritesheet uses the following motion rows:

- `idle` - still Isaac front-facing idle frame.
- `running-right` - right-facing walk cycle assembled from Isaac body/head sprites.
- `running-left` - left-facing walk cycle assembled from Isaac body/head sprites.
- `waving` - blink-style fail animation using hurt frames and blank frames.
- `jumping` - five-frame jump with squash motion.
- `failed` - eight-frame hurt/fail sequence.
- `waiting` - six selected frames from the Isaac drip GIF sequence.
- `running` - six selected frames from the Isaac drip GIF sequence.
- `review` - six selected frames from the Isaac chingon GIF sequence.

The GIF-derived rows are inserted into `192x208` Codex cells while preserving their original pixel proportions.

## Installation

Copy this folder into your Codex pets directory:

```text
~/.codex/pets/isaac-moriah
```

The final structure should look like this:

```text
isaac-moriah/
├── pet.json
└── spritesheet.webp
```

Restart or refresh Codex after installation.

## Disclaimer

This is an unofficial fan-made Codex pet.

All copyrights for the original sprites belong to the developers, publishers, and rights holders of *The Binding of Isaac: Rebirth*. Copyrights for GIF-derived animation material belong to the original GIF creators and their respective rights holders.

I do not claim ownership of the original game sprites, GIFs, characters, artwork, or any related intellectual property. This repository only packages adapted fan-made pet assets for personal Codex use.
