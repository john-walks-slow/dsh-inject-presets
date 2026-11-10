# dsh-inject-presets

Prompt presets that [dsh-inject](https://github.com/john-walks-slow/dsh-inject) imports at runtime instead of shipping inside the plugin package.

- `dsh-purge.md` — the community dsh-purge jailbreak prompt, verbatim. Taken from dsh-purge v1.1.71 by **YuJunZhiXue（小杨）** (MIT License, `Copyright (c) 2026 小杨`; original repository removed, mirror: [mmparko/dsh-purge](https://github.com/mmparko/dsh-purge)). The upstream attribution request and non-commercial term carry over: no paid resale, no course or token bundling.
- `nsfw.json` — an adult-fiction preset: scene-setting turns plus age/identity neutralisation rules, imported as a normal preset.

## Use

In DSH: **Settings → dsh-inject → Import / Export → Preset library**, then import `dsh-purge 破甲稿` or `NSFW`. The plugin fetches the file from this repository (raw.githubusercontent.com, with a jsDelivr fallback) and stores it in your local config; nothing is fetched again after import.

Or import by URL under **Custom link import**:

- `https://raw.githubusercontent.com/john-walks-slow/dsh-inject-presets/main/dsh-purge.md`
- `https://raw.githubusercontent.com/john-walks-slow/dsh-inject-presets/main/nsfw.json`

These files are prompt text, not code. This repository is not an installable DSH plugin.

## License

MIT. `dsh-purge.md` remains under its upstream MIT license and attribution, as noted above.