# Omarchy Jade Crane Theme

Celadon mist, carved jade, and gold leaf — a light [Omarchy](https://omarchy.org)
theme drawn from a Guofeng landscape of jade mountains, red-crowned cranes, and
lucky clouds.

![Jade Crane preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/rafalyovson/omarchy-jade-crane-theme
```

Or via **Install → Style → Theme** and paste that URL.

## Palette

| Role | Hex | Note |
| --- | --- | --- |
| Background | `#f0efe6` | parchment mist |
| Foreground | `#1e3a2f` | forest ink, 10.7:1 |
| Accent | `#2f7a56` | deep jade, 4.5:1 |
| Active item | `#74b08e` / `#142820` | gum Yes/No, menus, terminal selection |
| Soft selection | `#c5d6c9` | btop rows, sidebars |
| Muted | `#556b60` | 5.0:1 |
| Red | `#c43a30` | crane crown |
| Yellow | `#806200` | gold leaf |
| Orange | `#a35214` | |
| Brown | `#7a4e30` | pine bark |

Every normal ANSI color is at least 4.5:1 on the background (WCAG AA for text),
and every bright color at least 3.5:1. Yellow, orange and brown are separate
hues, so they read differently in `git`, `ls` and prompts. Full palette in
[`colors.toml`](colors.toml). Icons are `Yaru-sage`.

## Wallpapers

| File | Size | |
| --- | --- | --- |
| `01-jade-crane.webp` | 6688×3764 | the full landscape |
| `02-crane-flight.webp` | 3800×1628 | 21:9 crop of the cranes, open sky on the right for windows |
| `omarchy.webp` | 3840×2160 | Omarchy logo in jade on parchment |

Cycle with `Super + Ctrl + W`. Art notes and license details are in
[CREDITS.md](CREDITS.md).

## Boot and login screen

`unlock.png` is a transparent, feathered crop of the cranes, so it blends into
the parchment background on the disk-unlock and login screens. Pick it under
**Style → Unlock**, or run:

```bash
omarchy plymouth set by theme jade-crane
```

## License

MIT — see [LICENSE](LICENSE).
