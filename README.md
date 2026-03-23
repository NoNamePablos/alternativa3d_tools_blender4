# Alternativa3D Tools — Blender 4.x Port

A port of the [Alternativa3D Tools](https://github.com/davidejones/alternativa3d_tools) Blender addon for **Blender 4.0+**.

## Credits

**Original author:** [David E Jones](http://davidejones.com) — [GitHub](https://github.com/davidejones/alternativa3d_tools)

This is a community port of David's plugin, updated to work with Blender 4.x API changes (node-based materials, updated Python API, etc.).

## What works

- Import/Export of `.a3d` files
- Export to Alternativa3D ActionScript classes
- Materials are created using Principled BSDF node setup (Blender 4.x compatible)
- Texture import (diffuse, normal, specular, opacity, etc.)

## Known Issues

- **Animations do not work** — animated data imports but animations are not properly merged/combined.骨ные анимации не склеиваются при импорте.
- This is a work-in-progress port; please report any issues.

## Installation

1. Download `io_alternativa3d_tools.py`
2. In Blender: `Edit → Preferences → Add-ons → Install...`
3. Select the downloaded `.py` file
4. Enable the addon in the list

## Compatibility

- Blender **4.0+** (tested on 4.0 – 4.x)
- Original plugin was designed for Blender 2.7x

## License

This port retains the original license from [davidejones/alternativa3d_tools](https://github.com/davidejones/alternativa3d_tools).
