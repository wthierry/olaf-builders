# Olaf Builders

Robot 3D printing project workspace for models, reference assets, firmware, software, electronics notes, and build documentation.

## Repository Layout

- `models/source/` - editable source model files such as Blender or ZBrush projects.
- `models/exported/` - exported model parts organized by assembly or source.
- `models/print-ready/` - parts intended to go directly to the slicer.
- `assets/reference-images/` - visual references and design images.
- `firmware/` - microcontroller firmware.
- `software/` - host-side tools, scripts, simulators, or control software.
- `hardware/electronics/` - wiring notes, schematics, BOMs, and controller documentation.
- `docs/` - build notes, assembly guides, and project decisions.

Large binary assets are configured for Git LFS in `.gitattributes`.
