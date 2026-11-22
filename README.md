# game-config_dontdelete

Remote config documents for the Capsule Pop and Flutter Path games (CAGameKit `remoteConfig.url`).
The games download these files at launch and layer them over their shipped `GameConfig.json`.

**Do not delete or rename this repository**: released games read from these URLs.

- `capsulepop.json` → https://cngzkrs.github.io/game-config_dontdelete/capsulepop.json
- `flutterpath.json` → https://cngzkrs.github.io/game-config_dontdelete/flutterpath.json

Rules: public on purpose (the same values ship inside the apps). Never put keys, passwords, tokens or personal data here.
Each file must stay a valid JSON object; an empty object `{}` means "use the shipped values". The games clamp every value to a safe range.
