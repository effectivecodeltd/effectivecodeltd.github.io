# Effective Code — logo

A high-contrast italic **e** (the studio's initial) set on the flame squircle,
drawn from the brand's own typeface. The italic echoes the site's
italic-for-emphasis voice; the optional hairline incision in `mark-break`
expresses the studio's line — *built, and broken*.

All letterforms are **outlined** (real vector paths, no font dependency), so
every file renders identically as a favicon, in print, or on social cards.

## Files

| File | Use |
|------|-----|
| `mark.svg` | Primary mark — white `e` on flame squircle. Default everywhere. |
| `mark-break.svg` | Expressive variant with the hairline "break" score. Hero / large formats. |
| `mark-light.svg` | Reversed — flame `e` on a soft paper tile with keyline. Light/busy backgrounds. |
| `mark-ink.svg` | One-colour (ink) version for stamps and mono print. |
| `glyph-e.svg` | The `e` alone, no tile. |
| `lockup.svg` | Horizontal lockup — mark + "Effective Code" wordmark. |
| `lockup-ink.svg` | One-colour lockup. |
| `favicon.svg` | Browser tab icon (wired into `index.html`). |
| `apple-touch-icon.png` | 180×180 home-screen icon. |
| `og-image.png` | 1200×630 social / Open Graph card. |
| `mark-1024.png`, `mark-break-1024.png`, `lockup-1024.png` | Raster exports (app icon, etc.). |

## Palette

| Token | Hex |
|-------|-----|
| Flame | `#E0381F` |
| Paper | `#F4F1E9` |
| Paper deep | `#ECE8DD` |
| Ink | `#16130F` |

## Clear space & minimum size

Keep clear space of at least the tile's corner radius on all sides. The mark
stays legible down to 16px; below that, prefer `glyph-e.svg`.

## Type

Wordmark is **Fraunces** (OFL), the site display face. Outlines are baked in,
so the font is not required to render these files.
