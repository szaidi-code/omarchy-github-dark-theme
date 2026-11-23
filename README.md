# Destiny 2 for Omarchy

A dark [Omarchy](https://omarchy.org/) theme inspired by **Destiny 2**, featuring deep slate-navy surfaces, Traveler gold (`#e3c059`) and Arc cyan (`#45c8ff`) accents, and five high-resolution wallpapers.

## Install

Clone the `destiny-2` branch directly into your Omarchy themes directory and apply it:

```bash
git clone -b destiny-2 --single-branch https://github.com/szaidi-code/omarchy-github-dark-theme.git ~/.config/omarchy/themes/destiny-2
omarchy theme set destiny-2
```

Update later with:

```bash
omarchy theme update
```

## Wallpapers

Five WebP wallpapers are included in `backgrounds/`:

- `1-traveler-orbit.webp` (`3840×2160`) *(default)*
- `2-scarlet-keep-luna.webp` (`3840×2160`)
- `3-europa-pyramid.webp` (`3840×2160`)
- `4-traveler-last-city.webp` (`2880×1800`)
- `5-collapsed-frontier.webp` (`3840×2160`)

Cycle wallpapers anytime with:

```bash
omarchy theme bg next
```

## Palette

| Role | Hex |
| --- | --- |
| Canvas (`background`) | `#12161f` |
| Deep surface (`dark_background`) | `#0c0f16` |
| Inset / deepest (`darker_background`) | `#080a0f` |
| Raised surface (`lighter_background`) | `#1c2230` |
| Primary text (`foreground`) | `#e6eaf2` |
| Secondary text (`light_foreground`) | `#bcc5d6` |
| Muted text (`dark_foreground`) | `#6e7b94` |
| Border / muted (`muted`) | `#49546b` |
| Selection (`selection`) | `#243047` |
| Accent / gold (`accent`, `yellow`) | `#e3c059` |
| Active border (`hyprland_active_border`) | `rgba(e3c059ee) rgba(45c8ffee) 45deg` |
| Inactive border (`hyprland_inactive_border`) | `rgba(2a3347aa)` |
| Arc (`cyan`) | `#45c8ff` |
| Solar (`orange`) | `#ff7b2e` |
| Void (`magenta`) | `#a663eb` |
| Strand (`green`) | `#2dd980` |
| Danger (`red`) | `#e84d5b` |

## What's Included

- **`colors.toml`** — Canonical Omarchy semantic palette (`mode = "dark"`, Hyprland borders, full ANSI + bright colors).
- **`backgrounds/`** — Five WebP wallpapers.
- **`icons.theme`** — `Yaru-yellow-dark` icon theme matching `#e3c059`.
- **Zero restricted files** — No `.lua`, terminal launch configs, or `vscode.json` are shipped, so the theme applies cleanly without warnings.

## Other Themes in This Repository

- **[GitHub Dark (`main`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/main)**
- **[Halo (`halo`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/halo)**
- **[Neon Rain (`neon-rain`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/neon-rain)**

## License

[MIT](LICENSE), copyright 2026 szaidi-code.
