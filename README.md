<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="svg/simplebuild-logo-dark.svg">
    <img alt="simplebuild — Rapid C++ &amp; Python Development" src="svg/simplebuild-logo.svg" width="560">
  </picture>
</p>

# simplebuild logo

The official logo of [simplebuild](https://github.com/mctools/simplebuild): a terminal prompt
where you type `sb`, followed by build output that ends in a passing test. It stands for the
quick edit–build–test cycle simplebuild gives mixed C++ and Python projects.

All text is converted to outlines, so no fonts are needed to display any of the files.
Except where noted, backgrounds are transparent.

![All variants of the simplebuild logo on light and dark backgrounds, plus web and social images](preview.png)

## Usage note

You are welcome to use the simplebuild logo to refer to simplebuild, for example in talks,
papers, posters, websites, and in projects built with simplebuild. When doing so:

- Use the files as provided, scaled proportionally. Please don't alter the proportions,
  colours or arrangement of the logo, or combine it with other marks.
- Pick the variant that suits the background: the dark variants on dark backgrounds, the
  one-colour variants where colour isn't possible.
- Don't use the logo in a way that suggests simplebuild or its developers endorse a product,
  service or organisation, unless they actually do.

## Variants

| Suffix | Use on | Example |
|---|---|---|
| *(none)* | light pages | <img src="svg/simplebuild-logo-compact.svg" height="28" alt="light"> |
| `-dark` | dark pages (e.g. GitHub dark) | [simplebuild-logo-dark.svg](svg/simplebuild-logo-dark.svg) |
| `-mono-black` | one-colour print, light backgrounds | <img src="svg/simplebuild-logo-compact-mono-black.svg" height="28" alt="one colour, black"> |
| `-mono-white` | one colour on dark backgrounds, gradients or photos | [simplebuild-logo-mono-white.svg](svg/simplebuild-logo-mono-white.svg) |

The dark and white variants use white text, so they are hard to see on GitHub's light
theme; [preview.png](preview.png) shows them all on suitable backgrounds.

The one-colour versions are drawn in a single ink with the prompt, text and output lines
cut out, so whatever is behind them (including gradients) shows through; the disc has a
thin outer ring.

## Shapes

| Shape | Files | Light version |
|---|---|---|
| **Logo**: icon, name and tagline | `simplebuild-logo…` | <img src="svg/simplebuild-logo.svg" height="56" alt="logo"> |
| **Compact logo**: icon and name, sized to sit inline in text | `simplebuild-logo-compact…` | <img src="svg/simplebuild-logo-compact.svg" height="32" alt="compact logo"> |
| **Icon**: the disc alone, square | `simplebuild-icon…` | <img src="svg/simplebuild-icon.svg" height="56" alt="icon"> |

## Folders

| Folder | Contents |
|---|---|
| [`svg/`](svg/) | Vector master files: logo, compact logo and full-detail icon for every variant |
| [`svg/icon-small-sizes/`](svg/icon-small-sizes/) | The icon redrawn for small sizes: 96, 64 and 32 px detail levels |
| [`pdf/`](pdf/) | Vector PDFs of the logo, compact logo and icon (for pdfLaTeX papers and Beamer) |
| [`png/icon/`](png/icon/) | Icon at 16, 24, 32, 48, 64, 96, 128, 180, 192, 256, 512, 1024, 2048 px |
| [`png/logo/`](png/logo/) | Logo at heights 64, 128, 256, 512, 1024, 2048 px |
| [`png/logo-compact/`](png/logo-compact/) | Compact logo at heights 24, 32, 48, 64, 128, 256, 512 px |
| [`web/`](web/) | Favicons and app icons (see below) |
| [`social/`](social/) | Share images and avatars, on solid backgrounds |

**About the small sizes.** The icon simplifies as it shrinks: above 96 px it shows three
output lines; at 65–96 px two lines; at 33–64 px one line; at 32 px and below only the
prompt and `sb`. Every PNG already uses the right level. If you scale an SVG yourself, pick
the nearest file from [`svg/icon-small-sizes/`](svg/icon-small-sizes/) for anything below
about 128 px. The compact logo always uses the 64 px level, since it is meant to be small.

| 16 px | 32 px | 64 px | 96 px | full detail |
|:-:|:-:|:-:|:-:|:-:|
| <img src="png/icon/simplebuild-icon-16.png" alt="16 px"> | <img src="png/icon/simplebuild-icon-32.png" alt="32 px"> | <img src="png/icon/simplebuild-icon-64.png" alt="64 px"> | <img src="png/icon/simplebuild-icon-96.png" alt="96 px"> | <img src="png/icon/simplebuild-icon-256.png" width="128" alt="full detail"> |

Logo files are trimmed to the artwork with a ~2% margin; add clear space where you place them.

## Web

| File | Purpose |
|---|---|
| [`web/favicon.ico`](web/favicon.ico) | Classic favicon, contains 16, 32 and 48 px |
| [`web/favicon.svg`](web/favicon.svg) | Modern browsers; switches automatically between light and dark |
| [`web/apple-touch-icon.png`](web/apple-touch-icon.png) | iPhone/iPad home screen, 180 px, white background |
| [`web/android-chrome-192x192.png`](web/android-chrome-192x192.png), [`-512x512`](web/android-chrome-512x512.png) | Android / web app manifest |
| [`web/maskable-icon-192x192.png`](web/maskable-icon-192x192.png), [`-512x512`](web/maskable-icon-512x512.png) | Android adaptive icon (safe-zone padding, white background) |

```html
<link rel="icon" href="/favicon.ico" sizes="48x48">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
```

```json
{
  "name": "simplebuild",
  "icons": [
    { "src": "/android-chrome-192x192.png", "sizes": "192x192", "type": "image/png" },
    { "src": "/android-chrome-512x512.png", "sizes": "512x512", "type": "image/png" },
    { "src": "/maskable-icon-512x512.png", "sizes": "512x512", "type": "image/png", "purpose": "maskable" }
  ]
}
```

## Social

| File | Purpose |
|---|---|
| [`social/github-social-preview-1280x640.png`](social/github-social-preview-1280x640.png) (+ [`-dark`](social/github-social-preview-dark-1280x640.png)) | GitHub repository → Settings → Social preview |
| [`social/share-image-1200x630.png`](social/share-image-1200x630.png) (+ [`-dark`](social/share-image-dark-1200x630.png)) | Open Graph / link previews on other sites |
| [`social/avatar-1024.png`](social/avatar-1024.png) (+ [`-dark`](social/avatar-dark-1024.png)) | Square avatar |

## Snippets

A README logo that follows the reader's light or dark theme. Within this repository use
relative paths as here; from another repository, use the files' "raw" URLs, i.e.
`https://raw.githubusercontent.com/<owner>/<repo>/<branch>/svg/simplebuild-logo.svg`.

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="svg/simplebuild-logo-dark.svg">
  <img alt="simplebuild" src="svg/simplebuild-logo.svg" height="96">
</picture>
```

The compact logo inline in HTML text, sized so "simplebuild" matches the surrounding text and
sits on its baseline:

```html
… built with <img src="simplebuild-logo-compact.svg" alt="simplebuild"
  style="height:0.943em; vertical-align:-0.165em"> in seconds …
```

LaTeX (inline, roughly matching the text):

```latex
\raisebox{-0.165em}{\includegraphics[height=0.943em]{simplebuild-logo-compact.pdf}}
```

These numbers are for the light compact logo. The others are slightly taller because of their
rim or ring: use `height:0.964em; vertical-align:-0.166em` for `-dark` and
`height:0.995em; vertical-align:-0.166em` for the one-colour versions.

## Colours

| | Light | Dark |
|---|---|---|
| Disc | `#0A5A85` | `#2D6685` |
| Disc rim (full-detail icon) | `#063852` | `#A4BDCA` |
| Prompt chevron | `#FFD27A` | `#FFD27A` |
| `sb` | `#FFFFFF` | `#FFFFFF` |
| Cursor | `#F58A3C` | `#F58A3C` |
| Output lines | `#84ACC2` | `#93B1C0` |
| Passing-test check | `#4CC27A` with a white tick | same |
| "simplebuild" | `#09527A` | `#FFFFFF` |
| Tagline | `#1C6288` | `#A4BDCA` |

The small-size icons (96 px and below) have no rim on light backgrounds. One-colour versions
use pure `#000000` or `#FFFFFF`.

## Typefaces

"simplebuild" and the `sb` in the icon are set in **Outfit Bold** (Copyright 2021 The Outfit
Project Authors), with the tail of the *p* shortened as the *y* is in the NCrystal logo; the
tagline is **Source Sans 3 Bold** (Copyright 2010–2020 Adobe, with Reserved Font Name
"Source"). Both are licensed under the [SIL Open Font License 1.1](https://openfontlicense.org)
(OFL). These are the same typefaces as in the [NCrystal](https://github.com/mctools/ncrystal)
and [MCPL](https://github.com/mctools/mcpl) logos.

- **The logo files contain no fonts.** All letters were converted to plain vector shapes,
  so these files do not distribute font software, and the OFL's conditions do not apply
  to them.
- **Use is unrestricted.** The OFL allows the fonts to be used for any purpose, including
  logos and commercial work, with no fee and no attribution required in the artwork.
- **Shortening the *p*** edits the logo drawing, not the font, so it is not a "Modified
  Version" in the OFL's sense.
- **The OFL's restrictions only concern the font files themselves:** they may not be sold
  on their own; a modified font must not use the original name (for Source Sans 3, "Source"
  is a reserved name and an Adobe trademark); and if the font files are redistributed, the
  licence text must accompany them.
- **To recreate or edit the logo text**, get the fonts from Google Fonts:
  [Outfit](https://fonts.google.com/specimen/Outfit) and
  [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3).

## License

The files in this repository are licensed under the [Apache License 2.0](LICENSE).
As stated in its section 6, that licence does not grant permission to use the simplebuild
name or logo as a trademark beyond what is needed to describe the origin of the work;
the [usage note](#usage-note) above describes how the project would like the logo used.
