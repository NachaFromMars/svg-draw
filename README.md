# svg-draw — Generate SVG illustrations and convert to PNG, no graphics libs

> Write pure SVG code and convert to PNG using system `rsvg-convert` — no PIL, no ImageMagick. Pre-built templates for dragons, avatars, logos, and more in the assets/ folder.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
svg-draw generates vector graphics using hand-written SVG code and converts them to PNG using the system `rsvg-convert` tool. No heavy Python graphics libraries required. The `assets/` directory includes existing SVG templates (dragon, lobster, and others) as starting points. Use it for custom illustrations, avatars, logos, or any artwork that can be expressed in SVG.

## Features
- **Pure SVG** — no PIL, no ImageMagick, no heavy dependencies
- **PNG conversion** — `rsvg-convert` system tool
- **Template library** — `assets/` folder with existing SVG templates
- **Covers** — illustrations, avatars, logos, artwork

## Usage / Quick Start
```bash
# 1. Write SVG to file (or use a template from assets/)
cat > output.svg << 'EOF'
<svg width="400" height="400" xmlns="http://www.w3.org/2000/svg">
  <!-- your SVG content -->
</svg>
EOF

# 2. Convert to PNG
rsvg-convert output.svg -o output.png
```

## Trigger Keywords (OpenClaw)
draw image, create SVG, make illustration, draw dragon, create avatar, make logo, SVG to PNG, generate image

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
