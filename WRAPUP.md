# Wrapup — GitHub profile (joet203)
*Last updated: 2026-06-23 15:37*

## Where I left off
- Full GitHub-profile overhaul complete. Profile (github.com/joet203) now leads with a README + AI-first bio + 6 curated pins of real work (zero forks).
- **4 new public repos shipped this session** (all secret-scanned via gitleaks, MIT-licensed, described, topic-tagged, `main` branch):
  - `joet203/muse` — WebAudio synth (made public from private)
  - `joet203/claude-code-toolkit` — NEW repo: curated Claude/Codex skills + kitty add-ons
  - `joet203/snipshot` — Android Kotlin auto-crop tool (made public)
  - `joet203/wellness-vision-generator` — NEW repo: clean code-only copy of the private `wellviz`
- `joet203/joet203` profile README repo created (intro + technical capabilities + selected-projects table).
- Profile **bio set** and **name** = "Joe Toch" (reverted from "Joe Tochka" per JT's request; README + LICENSEs updated to match).
- Pinned 6: habit-tracker-app, kobala-telegram-bot, magic-box, procedural-arcade-racer (renamed from cop-takedown), secret-of-donut-mountain, claude-code-toolkit.
- All 9 touched repos got sharpened descriptions.

## What's unfinished
- **snipshot demo GIF/screenshots** — README has a Demo placeholder + `docs/` dir wired, but the actual GIF needs JT's physical Pixel (`adb screenrecord`). This is the one thing blocking snipshot from being pin-worthy.
- `movie-service` (leaked recruiter take-home) still **public** — recommended making private, JT hasn't actioned it.
- `wellviz` original repo stays **private + untouched** (live Azure app on branch `dev`, has student PII in history — deliberately not published; the clean `wellness-vision-generator` is the public face).
- Other junk public repos (`temp`, `vanilla`, `imagesorter`, `comfy-setup`, `epstein-files`) still public — flagged but not cleaned.

## Next steps
1. JT: capture snipshot demo GIF on Pixel, drop in `~/ss/snipshot/docs/`, uncomment the README image line.
2. (Optional) Make `movie-service` private: `gh repo edit joet203/movie-service --visibility private --accept-visibility-change-consequences`.
3. (Optional) Clean up junk public repos.
4. (Optional) Add topics/descriptions to JT's other public repos (civic-action pages, podcast-transcription-pipeline).

## Key decisions made
- **Pins curated for AI-eng job hunt**: 2 AI + full-stack + game + hardware + dev-tooling. Dropped survivor-prediction-tracker for claude-code-toolkit.
- **cop-takedown renamed → procedural-arcade-racer** + reframed README/description (defuse "shoot cops" framing for recruiters; kept all procedural-tech substance).
- **wellviz NOT published directly** — student PII in git history + live Azure deploy. Published a fresh-history code-only mirror instead.
- **claude-code-toolkit curation**: excluded personal skills (cover-letter, job-intel, companion, resume-tailoring) and the 2 hyper-specific codex skills (candy-jungle, forza-6); genericized all `JT`/path/team-slug references.
- Bio path: API blocked (gh token lacks `user` scope) → set via browser form.

## Files touched
- `~/gh-profile/README.md` (NEW — profile README) + `WRAPUP.md`
- `~/claude-code-toolkit/` (NEW repo — README, kitty/README, LICENSE, skills/, plugins/, kitty/)
- `~/wellness-vision-generator/` (NEW repo — code-only mirror of ~/wellviz + new README)
- `~/ss/snipshot/` — LICENSE, README (demo section), `CLAUDE.md`→`ENGINEERING_NOTES.md` (sanitized)
- `~/ss/snipshot-publish-report.html` (NEW — polka-dot publish-readiness report)
- GitHub-side (via gh/browser): muse public, snipshot public, descriptions on 9 repos, pins x2, bio, name
