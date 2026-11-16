# Graph Paper Dark for Omarchy

A dark graph-paper theme for [Omarchy](https://omarchy.org/): deep slate surfaces, precise grid lines, and cool ink accents inspired by engineering notebooks and blueprint paper.

![Graph Paper Dark preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/abhinavbxr/omarchy-graph-paper-dark-theme
```

## Try locally

Copy this folder into your Omarchy themes directory and apply it:

```bash
cp -r /path/to/graph-paper-dark ~/.config/omarchy/themes/
omarchy theme set graph-paper-dark
```

## Backgrounds

- `backgrounds/01-graph-paper.png` — generated dark graph-paper wallpaper (2560×1440)

Cycle backgrounds with `omarchy theme bg next`.

## Palette

Defined in `colors.toml`:

| Role | Color |
| --- | --- |
| Background | `#1b2430` |
| Foreground | `#d8e0ea` |
| Accent | `#7aa2c7` |
| Selection | `#33445a` |
| Muted | `#5b6f86` |

Omarchy generates application themes from `colors.toml`.

## Files

- `colors.toml` — core theme palette
- `icons.theme` — icon theme name (`Yaru-blue-dark`)
- `backgrounds/` — theme wallpapers
- `preview.png` — 16:9 theme preview image (1600×900)
- `preview.webp` — 16:9 web preview asset (1200×675), ready to replace with a community-submission screenshot

## Community theme compatibility

Prepared for [omarchy-site community theme submission guidelines](https://github.com/omacom/omarchy-site#adding-your-theme) (not submitted):

- Theme is installable from its own repository URL and keeps required theme files (`colors.toml`, `icons.theme`, `backgrounds/`, previews, docs).
- Includes a 16:9 web preview asset (`preview.webp`, 1200×675, <100KB).

**Before submitting to the community gallery:** replace the preview with a real 16:9 desktop screenshot of the theme in use (terminal + editor visible, using this theme’s wallpaper, no cursor/notifications/personal info), then convert as recommended:

```bash
magick preview.png -strip -resize '1200>' -quality 80 graph-paper-dark.webp
```

Use the resulting image as the site submission screenshot (e.g. `assets/themes/graph-paper-dark.webp` in `omarchy-site`) and add the theme entry to `themes/index.html`.

## License

MIT
