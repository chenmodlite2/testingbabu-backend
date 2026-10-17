# CHEN TOOL · Backend

Public host for the CHEN TOOL app backend (served over HTTPS by GitHub):

- `keys.json`   — license keys (SHA-256 hashes only)
- `config.json` — app update config
- `panel/`      — admin panel → https://chenmodlite2.github.io/testingbabu-backend/panel/

The Android app reads `keys.json` / `config.json` from the raw URLs of this repo.
Manage keys & updates from the panel (SETUP tab: owner / repo / branch / token).
