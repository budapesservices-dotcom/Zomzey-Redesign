# ZOMZEY UI Library

A lightweight, live component library for the ZOMZEY redesign. The library starts with one component: the pattern-wipe btn-12 button, adapted from the Uiverse.io design supplied for this project and recolored with the provisional Signal Network palette.

## Current component

- Primary button: Midnight Ink background, Electric Lime pattern wipe, pill radius, uppercase label.
- Interaction: two striped layers slide in from opposite directions on hover.
- Accessibility: keyboard focus visibility, disabled-state styling, and reduced-motion support.

## Design tokens

The current palette is a proposal for this redesign, not a claim about ZOMZEY's official brand colors:

- Midnight Ink: #191622
- Electric Lime: #D6FF3F
- Digital Cobalt: #665BFF
- Warm Paper: #F6F4ED
- Signal Coral: #FF7557

## Structure

The homepage intentionally demonstrates only one button at the top-left. The component CSS is isolated in css/components.css; shared values live in css/tokens.css. There is no JavaScript dependency for the hover effect.

## Hosting

Static website deployed by GitHub Pages. No framework, build step, or paid design platform is required.

Future components should be added to this library only after their visuals and interactions have been approved.
