# Halo for Omarchy

A dark [Omarchy](https://omarchy.org/) theme inspired by **Halo**, featuring deep pine-slate surfaces, Spartan olive (`#84b853`) and visor gold (`#e5a93c`) accents, and five high-resolution wallpapers.

## Install

Clone the `halo` branch directly into your Omarchy themes directory and apply it:

```bash
git clone -b halo --single-branch https://github.com/szaidi-code/omarchy-github-dark-theme.git ~/.config/omarchy/themes/halo
omarchy theme set halo
```

Update later with:

```bash
omarchy theme update
```

## Wallpapers

Five WebP wallpapers are included in `backgrounds/`:

- `1-pelican-halo-ring.webp` (`3840×2160`) *(default)*
- `2-spartan-helmet-zeta.webp` (`3840×2160`)
- `3-zeta-halo-night.webp` (`3840×2160`)
- `4-halo-ring-horizon.webp` (`3840×2160`)
- `5-forerunner-spire-valley.webp` (`3700×2081`)

Cycle wallpapers anytime with:

```bash
omarchy theme bg next
```

## Palette

| Role | Hex |
| --- | --- |
| Canvas (`background`) | `#101512` |
| Deep surface (`dark_background`) | `#0b0e0c` |
| Inset / deepest (`darker_background`) | `#070908` |
| Raised surface (`lighter_background`) | `#19221d` |
| Primary text (`foreground`) | `#dce6df` |
| Secondary text (`light_foreground`) | `#b5c7bb` |
| Muted text (`dark_foreground`) | `#6c8273` |
| Border / muted (`muted`) | `#46574c` |
| Selection (`selection`) | `#1f3328` |
| Accent / Spartan olive (`accent`, `green`) | `#84b853` |
| Active border (`hyprland_active_border`) | `rgba(84b853ee) rgba(e5a93cee) 45deg` |
| Inactive border (`hyprland_inactive_border`) | `rgba(28362eaa)` |
| Visor gold (`yellow`) | `#e5a93c` |
| Cortana / holographic (`cyan`) | `#38d9f5` |
| Plasma blue (`blue`) | `#2998e6` |
| Covenant purple (`magenta`) | `#a966ff` |
| Danger (`red`) | `#e64c4c` |

## What's Included

- **`colors.toml`** — Canonical Omarchy semantic palette (`mode = "dark"`, Hyprland borders, full ANSI + bright colors).
- **`backgrounds/`** — Five WebP wallpapers.
- **`icons.theme`** — `Yaru-olive-dark` icon theme matching `#84b853`.
- **Zero restricted files** — No `.lua`, terminal launch configs, or `vscode.json` are shipped, so the theme applies cleanly without warnings.

## Other Themes in This Repository

- **[GitHub Dark (`main`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/main)**
- **[Destiny 2 (`destiny-2`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/destiny-2)**
- **[Neon Rain (`neon-rain`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/neon-rain)**

## License

[MIT](LICENSE), copyright 2026 szaidi-code.
