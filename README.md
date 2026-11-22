# animation-studio-scenes
2 nd

**Second repository of the Animation Studio project** (created 22 Nov by the Director when the main repo reached ~4.4 GB).

| Repository | Contains | Status |
|---|---|---|
| `animation-studio` (main) | Stage 1 characters · Stage 2 world (maps, TASK 04 blockout, TASK 05 terrain) · Stage 3 assets (TASK 06 vegetation libraries, LODs, populated regions) · ALL project rules (`CLAUDE.md`), `HANDOFF.md`, `STATUS.md`, `PROJECT_LOG.md` | finished stages — the asset library, never moved |
| `animation-studio-scenes` (this one) | Stage 4 scene-by-scene production (`04_scenes/`) · Stage 5 final animation + post (`05_post/`) | new work from Stage 4 onward |

**Both repositories must sit side by side in the same parent folder** (cloud session: `/home/user/animation-studio` + `/home/user/animation-studio-scenes`;
on the Director's PC e.g. `D:/Projects/animation-studio` + `D:/Projects/animation-studio-scenes`). Scene `.blend` files LINK the assets from
the main repo with relative paths (`//../../animation-studio/03_assets/...`) — nothing is copied, so the library stays in one place.

Final 4K renders / MP4 masters are NOT committed (size) — they live on the Director's PC / Drive (`05_post/final/` is git-ignored).
