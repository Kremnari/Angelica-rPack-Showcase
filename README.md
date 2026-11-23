# Angelica rPack Showcase

A Minecraft 1.7.10 resource pack demonstrating CTM (connected textures) extensions for
[Angelica](https://github.com/GTNewHorizons/Angelica).

## Version used for Angelica PR #2374

The pack as submitted with
[GTNewHorizons/Angelica#2374](https://github.com/GTNewHorizons/Angelica/pull/2374)
("[CTM] Transparency Pass and Multi-Layering") is on the
**[`PR-2374`](https://github.com/Kremnari/Angelica-rPack-Showcase/tree/PR-2374)** branch.
Use that branch to reproduce the PR's behavior; `main` may move ahead of it.

It covers:

- `renderLayer` stacking of multiple `ctm_compact` overlays on one face
- `connect=rlist` projected overlays
- Translucent, cutout and solid overlay passes
- `abuttingBlocks` gating
- `none` for empty compact tile slots (use this instead of fully transparent PNGs)

Notes:

- `oreDict:` entries need Angelica's separate `ctm-oredictionary` work, which is not part of #2374.
- `paneFacings.properties` is shipped with `disabled=true`: compact overlays on glass panes are not supported.
