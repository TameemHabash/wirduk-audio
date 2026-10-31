# wirduk-audio

Public files for the وِرْدُك (Wirduk) adhkar app, served by GitHub Pages:
`https://tameemhabash.github.io/wirduk-audio/`

| Path | What |
|---|---|
| `audio/ar/<name>.mp3` | Arabic adhkar recordings (397 files, about 184 MB), downloaded by the app on demand |
| `audio/ar/<dhikr id>.m4a` | The morning and evening adhkar recordings the app plays since 2026-10-31 (30 files, about 12 MB), named after the dhikr's id in the app |
| `privacy/` | The app's privacy policy (Arabic and English) |

The recordings are by the reciter حمد الدريهم. They come unchanged (no re-encoding) from
[rn0x/Adhkar-json](https://github.com/rn0x/Adhkar-json) (commit `93dc3fc`). The only change: one
file saved there without its `.mp3` extension is an exact copy of
`ar_7esn_AlMoslem_by_Doors_053.mp3`, so it is not included twice.

The `.m4a` recordings were given by the app's owner and are published as received (no
re-encoding). The `.mp3` files they replace stay here, so older versions of the app keep working.

The app checks each file's size against its own list. When files change here, the list in the app
must be updated too.
