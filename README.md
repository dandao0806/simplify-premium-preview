# Simplify Premium Preview — Interactive Prototype

A mobile-first interactive prototype of the Plymouth Rock quote review flow, built directly from Figma wireframes.

## Live demo

Once GitHub Pages is enabled, the prototype is available at:
**https://dandao0806.github.io/simplify-premium-preview/prototype.html**

Open it on a phone for the best experience — the layout drops the phone frame on small viewports and fills the device edge-to-edge.

## What's in it

- Main quote screen with 4 plan tiers: Price Conscious, Most Popular, Superior Coverage, Custom Made
- iOS status bar, sticky bottom bar with premium + CTA
- Bottom-sheet editors for Bodily Injury Liability, Package Coverage (Essential / Preferred / Premium), and Extra PIP options
- Per-field "Pending" state — only rows the user edited flip to Pending
- Recalculate flow: builds a Custom Made tier from the edits, shows the price-change delta, scrolls back to top
- Responsive: phone mockup on desktop/tablet, full-viewport app feel on mobile

## Tech

Single-file HTML/CSS/JS. No build step, no dependencies beyond Font Awesome and Google Fonts CDN. Open `prototype.html` directly in any modern browser.

## Enabling GitHub Pages

1. Repo settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `main`, folder: `/ (root)`
4. Save — the public URL appears within ~30 seconds
