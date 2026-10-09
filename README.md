# ZOMZEY UI Library

A lightweight component library for the ZOMZEY homepage redesign. This checkpoint refines the primary action using a **Human Signal** visual direction: distinctive and expressive, while remaining warm, clear, and trustworthy for a marketplace that connects people, creators, brands, shops, and communities.

## Current component

- Primary action: deep ink surface, a slim coral edge, and a two-layer coral/lilac pattern wipe.
- Interaction: the stripes arrive from opposite directions with 320 ms ease-in-out timing. Hover adds a small lift and a restrained shadow, not a neon glow.
- Accessibility: keyboard focus visibility, disabled-state styling, and reduced-motion support.
- Label: “Explore opportunities”, aligned with the marketplace's existing language.

## Provisional design tokens

These are design proposals, not confirmed official ZOMZEY brand colours:

- Ink: #20243A
- Signal Coral: #FF765E
- Soft Coral: #FFA38F
- Lilac: #C9BFFF
- Digital Violet: #575BE8
- Warm Paper: #F7F4EF

## Design rationale

The contest asks for a homepage that feels modern and unique without losing professionalism, trust, or intuitive navigation. The current dark, grid-heavy cyberpunk treatment has therefore been replaced by a light editorial canvas, a human-centred accent palette, and a memorable but restrained button interaction.

This repository currently demonstrates the button component only. It is not yet the full contest submission. The separate deliverables still include desktop and mobile homepage mockups, a concise style guide, and notes explaining the layout and interaction cues.

## Structure and hosting

The homepage intentionally demonstrates one button at the top-left. Component CSS is isolated in css/components.css; shared values live in css/tokens.css. The hover effect uses CSS only. GitHub Pages hosts the static preview without a framework or build step.
