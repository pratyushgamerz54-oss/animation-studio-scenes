# animation-studio-scenes — Claude rules (short)

1. **All project rules live in the main repo:** read `../animation-studio/CLAUDE.md` and `../animation-studio/HANDOFF.md` FIRST
   (Director rules: realism, motion / physics, VFX quality, 4K output, SAVE RULE). This file only adds the two-repo rules.
2. **Two repos, side by side:** `animation-studio` = characters / world / asset library (stages 1–3, frozen as a library) ·
   `animation-studio-scenes` = stage 4 scenes (`04_scenes/`) + stage 5 post (`05_post/`). Never copy library assets into this repo:
   LINK them (relative paths `//../../animation-studio/...`, `relative_remap=True` on save).
3. **Save:** the main repo's Stop hook (`../animation-studio/.claude/hooks/autosave.sh`) commits + pushes BOTH repos at every reply
   end (current branch, never force). Big binaries only at milestones; files > 95 MB never; final 4K renders / MP4 masters stay out of
   git (`05_post/final/`, `**/renders_4k/` ignored) → Director's PC / Drive.
4. Status / log for scene work: `STATUS_SCENES.md` here + the main `PROJECT_LOG.md` entry.
