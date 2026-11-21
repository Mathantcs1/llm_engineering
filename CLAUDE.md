# Project notes

## Faceless video skill
For any faceless YouTube Short or long video (script, build, render, mix, QC, upload text), use the skill in `.claude/skills/faceless-video-studio/` (read `SKILL.md` first). The render studio folder is not in this repo; ask the owner for the `growkaz-stickman-studio` folder.

Token rules (details: `.claude/skills/faceless-video-studio/references/token-efficiency.md`): start a fresh session per batch; avoid idle/status turns; one small frame sheet per video; do not read node_modules/build/raw media; measure with `scripts/token_report.sh`. Never put secrets in files.
