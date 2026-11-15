# doplan-assets

The **doplan asset feed**: on-demand models, materials and HDRIs for [doplan](https://github.com/totKtoXam/doplan).
The installer bundles only a small set; everything else in doplan's catalog is downloaded from here the first time it
is used (Settings → Asset sources, feed `doplan`). The files live in **releases**, not in git:

- release `feed-1`: `index.json` (id → file, sha256, size) and one `<entry id>.zip` per catalog entry, containing the
  entry's files under the library paths doplan's catalog names.

Format, custom feeds and how the feed is built (`pnpm assets:mirror`): see
[docs/ASSET-FEEDS.md](https://github.com/totKtoXam/doplan/blob/main/docs/ASSET-FEEDS.md) in the doplan repository.

## Licences and credits

Every file is **CC0 1.0** or **CC-BY-4.0**; [LICENSES.md](LICENSES.md) lists the sources and, for every CC-BY entry,
its author and source page (the same data is in each entry of doplan's `catalog.json`).

Sources: [Poly Haven](https://polyhaven.com) (CC0), [ambientCG](https://ambientcg.com) (CC0),
[Khronos glTF-Sample-Assets](https://github.com/KhronosGroup/glTF-Sample-Assets) (CC0 / CC-BY-4.0),
[KayKit Furniture Bits](https://github.com/KayKit-Game-Assets/KayKit-Furniture-Bits-1.0) (CC0),
[Sketchfab](https://sketchfab.com) models via the [Objaverse](https://huggingface.co/datasets/allenai/objaverse) mirror (CC-BY-4.0).

**Changes made to the originals:** JPEG textures were re-encoded with mozjpeg (colour q88, normal maps q85 without
chroma subsampling, roughness / AO / metalness as single-channel greyscale); files were renamed to doplan's library
paths. Geometry and other files are unchanged. These are not endorsed by the original authors.
