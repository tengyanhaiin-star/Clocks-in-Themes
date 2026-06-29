# Clocks in Themes

A collection of analog quartz clocks styled with 10 distinct visual themes, built as a single self-contained HTML file. Optimized for both desktop browsers and iOS Safari.

## Live Demo

Open [Clocks in Themes](https://tengyanhaiin-star.github.io/Clocks-in-Themes/) directly in any browser — no server, no dependencies, no build step required.

## Features

- **10 handcrafted themes**, each with its own color palette and typography
- **Real-time analog clock** with smoothly sweeping hour, minute, and second hands
- **Live date display** that updates each second
- **High-DPI / Retina rendering** via `devicePixelRatio` scaling for crisp output on all screens
- **iOS Safari optimized**: safe area insets, pinch-zoom disabled, touch-action tuned to prevent accidental full-screen exit
- **Instant theme switching** with a tap — no page reload

## Themes

| Theme | Character |
|---|---|
| Golden Hour | Warm autumnal palette — mustard, terracotta, chocolate |
| Ocean Depths | Deep navy and seafoam — calm and professional |
| Sunset Boulevard | Coral and amber — warm and inviting |
| Forest Canopy | Earthy greens and natural tones |
| Modern Minimalist | Clean greys — quiet and precise |
| Arctic Frost | Cool steel blue on near-white |
| Desert Rose | Dusty pink and plum — soft and elegant |
| Tech Innovation | Electric blue and cyan on near-black |
| Botanical Garden | Fresh greens and golden amber |
| Midnight Galaxy | Deep violet and lavender with neon accents |

## Fonts Used

| Theme | Typeface |
|---|---|
| Golden Hour, Desert Rose | Alatsi |
| Ocean Depths, Arctic Frost, Modern Minimalist | Alata |
| Sunset Boulevard, Botanical Garden | Yusei Magic |
| Forest Canopy | Do Hyeon |
| Tech Innovation, Midnight Galaxy | Monomaniac One |

All fonts are loaded from [Google Fonts](https://fonts.google.com). An internet connection is required for fonts to display correctly.

## Usage

1. Download `index.html`
2. Open it in any modern browser (Safari, Chrome, Firefox, Edge)
3. On iPhone: open in Safari → tap Share → **Add to Home Screen** for a full-screen web app experience

## Technical Notes

- Pure HTML5 Canvas — no frameworks, no build tools
- `requestAnimationFrame` loop for smooth animation
- `document.fonts.ready` ensures fonts are loaded before the first frame is drawn
- Canvas physical resolution is scaled by `window.devicePixelRatio` to eliminate noise and blurring on Retina screens
- All clock dimensions are expressed relative to radius `R` for consistent proportions

## License

MIT — see [LICENSE](LICENSE) for details.
