# DXVK for ElDewrito 0.7

## Patch updater for Windows

[Download ElDewrito DXVK Updater 1.0.2](https://github.com/duckfudge/eldewrito-dxvk/releases/tag/updater-v1.0.2).
Extract the entire ZIP and run `ElDewritoDXVKUpdater.exe`. Python is included.
Choose your game folder containing `eldorado.exe`; the app checks for patches when
opened and asks before installing. It also offers repair and restore controls.
Keep the game closed while installing or restoring a patch.

The updater manages `d3d9.dll`, `dxvk.conf`, and `eldorado.dxvk-cache`. It preserves
a backup of affected files, and normal shader-cache growth does not trigger updates.
Updater application downloads and DXVK patch releases are published separately.

[Updater source and maintenance documentation](https://github.com/duckfudge/eldewrito-dxvk-updater).

## Manual installation

How to use: Download the zip from https://github.com/duckfudge/eldewrito-dxvk/releases/latest and unzip the files into your ElDewrito folder.
You will have d3d9.dll, dxvk.conf, and eldorado.dxvk-cache in the same folder as eldorado.exe.

Support on HaloBase: https://discord.gg/PxPNNteChR

Caches merged with: https://github.com/Micro-Wave-Oven/dxvk-cache-tool

Credit to @microwave.oven. and @minelelol on Discord for their research and work into DXVK for ElDewrito.
