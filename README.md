# color-palette-harmonies

[![Live Demo](https://img.shields.io/badge/Live_Demo-palette.satyamsethi.dpdns.org-3b82f6?style=for-the-badge&logo=cloudflare&logoColor=white)](https://palette.satyamsethi.dpdns.org)
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-Deployment-F38020?style=for-the-badge&logo=cloudflarepages&logoColor=white)](https://color-palette-harmonies.pages.dev)

An interactive color harmony generator and WCAG 2.1 contrast analyzer with CSS variables export.

## 🌐 Live Demo

- **Primary Custom Domain**: [https://palette.satyamsethi.dpdns.org](https://palette.satyamsethi.dpdns.org)
- **Cloudflare Pages Direct**: [https://color-palette-harmonies.pages.dev](https://color-palette-harmonies.pages.dev)

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
