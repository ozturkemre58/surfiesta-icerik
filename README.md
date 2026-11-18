# surfiesta-icerik

Downloadable content for the game Surfiesta: character packs (Unity AssetBundles) the app fetches on demand.

Nothing here is source code. Each release `c<N>` holds the packs for app builds that read content version N:
`<platform>-packs.json` (the list: id, file, hash, CRC, size) and `<platform>-<id>.pack` for `android` and `ios`.

The packs are built and uploaded by `Tooling/content-build.sh` in the game's repository.
