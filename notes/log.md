# Log

Append-only record of all operations.

---

- **2026-11-18** — Setup: created `raw/`, `processed/`, `notes/`, `notes/index.md`, `notes/log.md`, and empty `raw/New_Notes.md`.
- **2026-11-18** — Ingested `raw/New_Notes.md` (5 URL notes):
  - Created `Agentic_Coding.md`: added the Spatial Thoughts course, the "Reflections on AI" article, and the Drew Breunig CNG 2026 keynote.
  - Created `Remote_Sensing.md`: added NASA ARSET.
  - Created `Data.md`: added the Cloud-Native Geospatial Forum YouTube channel.
  - Created related pages `Climate_Change.md`, `Agriculture.md`, and `Cartography.md` with back-links.
  - Updated `index.md`. Moved the source to `processed/New_Notes_2026-11-18.md` and created a new empty `raw/New_Notes.md`.
  - Note: YouTube pages returned limited metadata, so the channel and keynote descriptions are based on their titles.
- **2026-11-18** — Refreshed all pages to match the updated topic list in CLAUDE.md:
  - Removed `Agriculture.md`, `Climate_Change.md`, `Cartography.md`, and `Data.md`.
  - Created `Cloud_Native.md`: moved the Cloud-Native Geospatial Forum channel here from Data.
  - Created `Geospatial.md` (related to the Agentic Coding course and the CNG channel) and `Ecology.md` (related to NASA ARSET).
  - Updated back-links in `Agentic_Coding.md` and `Remote_Sensing.md`, and rebuilt `index.md`.
- **2026-11-18** — Ingested `raw/Evan Applegate (@youwillmakemaps) on X.md` (X post clipping):
  - Added a note on building websites with Claude Code to the top of `Agentic_Coding.md`.
  - Updated the Agentic Coding description in `index.md`.
  - Moved the source to `processed/`. `raw/New_Notes.md` was empty, so it stays in place.
- **2026-11-18** — Added the Web Design topic at the user's request:
  - Created `Web_Design.md` and moved the Evan Applegate note there from `Agentic_Coding.md`, adding the rybitten.space and Scrawl tool links.
  - Added a Related back-link from `Agentic_Coding.md` to Web Design.
  - Added Web Design to `index.md` under Thematic Topics and restored the original Agentic Coding description.
- **2026-11-18** — Set up website publishing from the spatialthoughts/personal-notes-website-template:
  - Added `mkdocs.yml` (site and repo set to bhass/notes, nav matches the current topic pages), `hooks.py`, `requirements.txt`, `.github/workflows/deploy.yml`, and `.gitignore` (plus Obsidian workspace files).
  - Changed `hooks.py` so the nav note counts skip Related wiki-link bullets and files are read as UTF-8.
  - Added a "Latest Finds" section to `index.md` and moved the topic list under "Topics".
  - Added an "Update the Website" section to `CLAUDE.md`.
  - The local `mkdocs build` succeeded.
- **2026-11-18** — Changed the GitHub repo in `mkdocs.yml` from bhass/notes to bridgethass/notes (site URL: https://bridgethass.github.io/notes/).
