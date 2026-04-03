# Changelog

Single file for Lite + Pro. **Lite** changes ship from this repo and `savestate-lite-*.zip` on [GitHub Releases](https://github.com/youssof20/savestate/releases). **Pro** is paid and only on [itch.io](https://chuumberry.itch.io/savestate-pro) — every Pro section below points there.

## v1.1.2

### Lite

- sample `samples/minimal-demo/` no longer copies the whole addon; copy `addons/savestate` from the repo or from the Lite zip before opening the project
- `addons/README.txt` in the sample explains the one-time copy step
- readme and quickstart updated so GitHub Releases is the place for the Lite zip only

### Pro

- [SaveState Pro on itch.io](https://chuumberry.itch.io/savestate-pro) — repackage your itch zip with Lite **1.1.2** plus Pro; include README + QUICKSTART only (no changelog inside the zip; changelog stays on GitHub)

## v1.1.1

### Lite

- `save_manager.gd` no longer names Pro-only `SaveSecurity` at parse time (fixes pure Lite projects and the sample)
- added `addons/savestate/encrypted_save_reader.gd` so Save Browser can still inspect Pro-encrypted outer saves when keys exist (same crypto as Pro)

### Pro

- [SaveState Pro on itch.io](https://chuumberry.itch.io/savestate-pro) — ship a bundle built against Lite **1.1.1** so editor health / dock behavior matches the Lite fix above

## v1.1.0

### Lite

- `samples/minimal-demo/` starter scene (move, gold, save/load)
- `migration_required(old_schema, new_schema)` on `SaveManager` when a loaded file schema is older than project setting `savestate/current_version`
- docs split: `docs/API.md`, `docs/ARCHITECTURE.md`, `docs/MIGRATION.md`
- readme trimmed; links to quickstart and docs
- GitHub Action publishes `savestate-lite-<tag>.zip` on each Release

### Pro

- [SaveState Pro on itch.io](https://chuumberry.itch.io/savestate-pro) — async save/load, optional encryption, Saveable inspector, debugger hooks, Save Browser extras; requires Lite enabled first; bundle Lite + Pro for itch buyers

## v1.0.0

### Lite

- first public Lite: atomic saves, rolling `.bak`, schema merge, `SaveManager` autoload, Save Browser dock

### Pro

- [SaveState Pro on itch.io](https://chuumberry.itch.io/savestate-pro) — initial paid addon (async, crypto, Saveable, editor tooling); sold and updated only on itch, not in this repo
