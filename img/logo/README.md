# Effective Code — logo

Two code brackets `[ ]` meet to form a hexagonal shield. It carries the studio's
three ideas at once: **brackets = code**, **shield = security**, and the two
mirrored halves (ink + flame) = the two practices, **build & break**.

Pure geometry — no font dependency in the mark — so every file renders
identically as a favicon, in print, or at billboard scale.

## Files

| File | Use |
|------|-----|
| `mark.svg` | Primary mark — ink left bracket, flame right bracket. Default everywhere. |
| `mark-ink.svg` | One-colour ink (mono print, stamps). |
| `mark-flame.svg` | One-colour flame. |
| `mark-reverse.svg` | For dark backgrounds — paper + flame brackets. |
| `icon-tile.svg` | Mark on a soft paper squircle, for app/home-screen icons. |
| `lockup.svg` | Horizontal lockup — mark + "Effective Code" wordmark (Fraunces). |
| `lockup-ink.svg` | One-colour lockup. |
| `favicon.svg` | Browser tab icon (heavier stroke for small sizes; wired into `index.html`). |
| `apple-touch-icon.png` | 180×180 home-screen icon (rendered from `icon-tile.svg`). |
| `og-image.png` | 1200×630 social / Open Graph card. |
| `mark-1024.png`, `lockup-1024.png` | Raster exports. |

## Palette

| Token | Hex |
|-------|-----|
| Flame | `#E0381F` |
| Paper | `#F4F1E9` |
| Paper deep | `#ECE8DD` |
| Ink | `#16130F` |

## Construction

A hexagon with vertices left/right (flat top & bottom). The outline is split into
two bracket halves with small gaps at top- and bottom-centre; left half ink,
right half flame. Stroke `≈ 0.34 × R`, gap half-width `≈ 0.14 × R`. The favicon
uses a heavier stroke and tighter gap so it survives 16px.

## Type

Wordmark is **Fraunces** (OFL), outlined into the lockup, so the font is not
required to render these files.

## Clear space & minimum size

Keep clear space of at least one bracket-width on all sides. The mark stays
legible to ~16px; the gaps simplify into a two-tone hex ring below that.
