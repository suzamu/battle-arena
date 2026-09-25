# Battle Arena — GTA 5 TikTok Live Gift Mod

**A Last Man Standing–style battle arena for GTA V, powered by TikTok Live.** Viewers send a gift during your stream and a ped instantly spawns in the arena carrying the weapon preset you configured. Every kill triggers random cute emotes, colorful kill texts, and randomly colored smoke — plus an MVP board, player name labels, gift tiers, and bomb detection.

Like *Last Man Standing*? This is the TikTok version of that idea: **interaction instead of a controller** — the audience plays with you through gifts.

**▶ Preview video:** https://youtu.be/WEKFry8HUzA
**💬 Discord:** https://discord.gg/tpxHnz6Kd6

## Features

- **TikTok gift webhook** — URL-based, callable from a bot or your phone
- **Weapon presets per URL** — `/unarmed`, `/mele`, `/pistol`, `/rifle`, `/rpg`, `/shotgun`, `/minigun` (add your own)
- **Any GTA ped model** — change it in the config
- **Kill effects** — 8 random kawaii emotes (different every kill), rainbow kill texts, randomly colored smoke
- **MVP board** — winner tracking per session
- **Player labels** — name + health bar above each ped
- **Automatic gift tiers** — small gifts vs big gifts spawn different tiers
- **Bomb detection** — `/bom`, `/nuke` commands
- **In-game menu (F3)** — start/stop arena, pick model, toggle labels
- **Live config reload** — edit the JSON while the game runs, changes apply instantly
- **One-click installer** — `PASANG.bat` (ScriptHookVDotNet + LemonUI included)

## How it works

```
TikTok gift -> webhook (port 6722) -> GTA V spawns a ped with a preset weapon
```

Test without TikTok: open `http://127.0.0.1:6722/` in a browser, or run the included fake-gift loop (1 gift every 10 seconds, random weapon).

## Requirements

- GTA V **PC** (Steam / Rockstar) — not for console
- [ScriptHookV](http://www.dev-c.com/gta5/) (any mod user already has this)

## Getting the mod

**Full version with installer — join the Discord:** https://discord.gg/tpxHnz6Kd6

> The repository itself contains documentation only. The mod is distributed as a compiled package to prevent redistribution.

## Videos

- **Preview / showcase:** https://youtu.be/WEKFry8HUzA
- Live clips: TikTok — see profile

## Disclaimer

- Not affiliated with, endorsed by, or sponsored by Rockstar Games or Take-Two Interactive.
- Use of mods in GTA Online is at your own risk (single-player / Story Mode recommended).
- Personal use only. No resale, re-upload, or redistribution.

## License

All rights reserved. See [LICENSE](LICENSE).

---

**Keywords:** battle arena gta 5, last man standing gta 5, last man standing alternative, gta 5 tiktok live, gta5 tiktok mod, tiktok gift gta 5, gta 5 gift arena, gta v script mod, tiktok live gta 5 interaction
