ROGUE TACTICS — SLICED SPRITES

Folders:
- characters/: separately cropped hero_XX and enemy_XX PNG images
- boss/: separately cropped boss_XX PNG images
- *_manifest.json: original crop coordinates and dimensions
- *_preview.jpg: contact sheets for quick inspection

Important:
The source sheets are hand-arranged illustrations, not strict uniform animation grids. The PNGs were extracted by transparent connected regions, so each file is a separate visible sprite/component, but the files are not guaranteed to be sequential animation frames or to have identical canvas sizes. The manifests preserve their crop coordinates. For runtime animation, define frame groups and timing in the game code after choosing which extracted poses belong together.
