# color-palette-harmonies

An interactive color harmony generator and WCAG 2.1 contrast analyzer with CSS variables export.

## What it does

Computes color harmonies (Complementary, Triadic, Analogous, Monochromatic tints/shades) mathematically via HSL color space, tests WCAG AA/AAA accessibility contrast ratios against light/dark themes, and exports ready-to-use CSS design tokens.

## Features

- **Mathematical Color Harmonies**: Automatically balances hues and saturations.
- **WCAG 2.1 Contrast Checker**: Instant compliance pass/fail indicator for dark & light mode backgrounds.
- **CSS Tokens Exporter**: Generates custom `:root` CSS variables.
- **Zero dependencies**: Pure vanilla JavaScript and HTML5.

## Setup

Requires Node.js (v14+). No external dependencies.

```bash
cd color-palette-harmonies
```

## Run command

```bash
node index.js
# Open http://localhost:3000
```
*(Or open `index.html` directly in any web browser)*
