# Neon Rain for Omarchy

A dark [Omarchy](https://omarchy.org/) cyberpunk theme featuring midnight-navy surfaces, electric cyan (`#00e5ff`) and hot magenta (`#ff2a85`) accents, and five 4K wallpapers.

## Install

Clone the `neon-rain` branch directly into your Omarchy themes directory and apply it:

```bash
git clone -b neon-rain --single-branch https://github.com/szaidi-code/omarchy-github-dark-theme.git ~/.config/omarchy/themes/neon-rain
omarchy theme set neon-rain
```

Update later with:

```bash
omarchy theme update
```

## Wallpapers

Five 4K (`3840×2160`) WebP wallpapers are included in `backgrounds/`:

- `1-neon-rain-avenue.webp` *(default)*
- `2-misty-harbour-skyline.webp`
- `3-victoria-harbour-neon.webp`
- `4-tokyo-midnight-corner.webp`
- `5-megacity-aerial.webp`

Cycle wallpapers anytime with:

```bash
omarchy theme bg next
```

## Palette

| Role | Hex |
| --- | --- |
| Canvas (`background`) | `#0d111a` |
| Deep surface (`dark_background`) | `#090c13` |
| Inset / deepest (`darker_background`) | `#06080d` |
| Raised surface (`lighter_background`) | `#161e2e` |
| Primary text (`foreground`) | `#dce8f5` |
| Secondary text (`light_foreground`) | `#b5c8de` |
| Muted text (`dark_foreground`) | `#687d9c` |
| Border / muted (`muted`) | `#465875` |
| Selection (`selection`) | `#1b334d` |
| Accent / neon cyan (`accent`, `cyan`) | `#00e5ff` |
| Active border (`hyprland_active_border`) | `rgba(00e5ffee) rgba(ff2a85ee) 45deg` |
| Inactive border (`hyprland_inactive_border`) | `rgba(24324aaa)` |
| Neon magenta (`magenta`) | `#ff2a85` |
| Electric blue (`blue`) | `#4d9aff` |
| Neon mint (`green`) | `#00f5a0` |
| Warm glow (`yellow`) | `#ffd166` |
| Danger (`red`) | `#ff3366` |

## What's Included

- **`colors.toml`** — Canonical Omarchy semantic palette (`mode = "dark"`, Hyprland borders, full ANSI + bright colors).
- **`backgrounds/`** — Five 4K WebP wallpapers.
- **`icons.theme`** — `Yaru-magenta-dark` icon theme matching `#ff2a85`.
- **Zero restricted files** — No `.lua`, terminal launch configs, or `vscode.json` are shipped, so the theme applies cleanly without warnings.

## Other Themes in This Repository

- **[GitHub Dark (`main`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/main)**
- **[Destiny 2 (`destiny-2`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/destiny-2)**
- **[Halo (`halo`)](https://github.com/szaidi-code/omarchy-github-dark-theme/tree/halo)**

## License

[MIT](LICENSE), copyright 2026 szaidi-code.
