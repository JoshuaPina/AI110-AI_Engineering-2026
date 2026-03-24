# AI110 AI Engineering (CodePath) — Master Repo

A master container for projects completed in the inaugural **AI Engineering (AI110)** CodePath course; this repo primarily tracks each week’s project as a Git submodule.

## Repository layout

- Each folder at the root (e.g., `week-1/`) is a **Git submodule** pointing to its own project repository.
- To clone with submodules: 
  
  ```bash
  git clone --recurse-submodules https://github.com/JoshuaPina/AI110-AI_Engineering-2026.git
  ```

- If you already cloned: 
  
  ```bash
  git submodule update --init --recursive
  ```

## Submodules

| Week | Path | Project | One-line description |
|------|------|---------|----------------------|
| 1 | `week-1` | Playlist Chaos (Debugging an AI-built Streamlit app) | Debug and harden an AI-generated Streamlit app that classifies songs into mood playlists (Hype/Chill/Mixed) with reliable search, stats, and “Lucky Pick.” |
| 3 | `week-3-main` | Game Glitch Investigator | Investigate and repair glitches in an AI-generated Python game using Copilot-guided debugging, refactors, and pytest verification. |

## Submodule sources

- Week 1 (`week-1`): `https://github.com/JoshuaPina/ai110-module1tinker-playlistchaos-starter`
- Week 3 (`week-3-main`): `https://github.com/JoshuaPina/ai110-module1show-gameglitchinvestigator-starter.git`

## Notes

- This repo is intended as an index/entry point; day-to-day development happens inside each submodule’s repository.
