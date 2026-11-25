# game-config_dontdelete

The public content store for Capsule Pop and Flutter Path (CAGameKit `remoteConfig.url`). The games download these
files at launch, layer `<game>.json` over their shipped `GameConfig.json` and fetch the pictures a season names.

**Do not delete or rename this repository, and do not move files that released games read.**

- `capsulepop.json` → https://cngzkrs.github.io/game-config_dontdelete/capsulepop.json
- `flutterpath.json` → https://cngzkrs.github.io/game-config_dontdelete/flutterpath.json
- `capsulepop/seasons/<season>/`, `flutterpath/seasons/<season>/`: each game's season pictures
- `shared/seasons/<season>/`: pictures any game may use

Public on purpose: anything a game downloads is public anyway. Only what is live or about to go live belongs here.
Sources, drafts, upcoming seasons and plans live in the private repo `game-content-workshop_dontdelete`.
Never put keys, passwords, tokens or personal data here. Each `<game>.json` must stay a valid JSON object; `{}` means
"use the shipped values". Picture paths in a season may be relative to this folder (`capsulepop/seasons/christmas/rail.jpg`).

How it all works and every season field: CAGameKit `docs/REMOTE_CONTENT.md`.
