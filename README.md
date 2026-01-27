# Vintage Decor

Starter scaffold for adding wallpaper and other interior decor to Vintage Story.

## Included
- `modinfo.json` with basic metadata
- Language stub at `assets/vintagedecor/lang/en.json`
- Wallpaper block definition at `assets/vintagedecor/blocktypes/wallpaper.json`
- Starter crafting recipe at `assets/vintagedecor/recipes/grid/wallpaper.json`
- Texture drop zone at `assets/vintagedecor/textures/block/wallpaper/`

## Next steps
1. Add your texture PNGs into `assets/vintagedecor/textures/block/wallpaper/` (e.g. `blank.png`, `floral.png`).
2. Duplicate or extend the `type` states in `assets/vintagedecor/blocktypes/wallpaper.json` to reference each texture you add.
3. Adjust the starter recipe in `assets/vintagedecor/recipes/grid/wallpaper.json` (currently flaxtwine or linen square → 9 wallpaper-blank, dyes recolor to variants) and duplicate it per pattern if you add more variants.
4. Optionally add more recipes, traders, or worldgen patches under `assets/vintagedecor/patches/`.
5. Test in a dev world; watch the client log for missing texture messages and adjust filenames accordingly.
