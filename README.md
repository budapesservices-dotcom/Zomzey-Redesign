# ZOMZEY UI Library

A lightweight, live component library for the ZOMZEY redesign. The first component is the pattern-wipe btn-12 button, adapted from the Uiverse.io design supplied for this project and restyled with the provisional Obsidian Prism palette.

## Current component

- Primary button: deep-space navy surface, ion-cyan and ultraviolet pattern wipe, squared corners, and a controlled luminous edge.
- Interaction: two striped layers slide in from opposite directions with smooth ease-in-out timing; hover adds a restrained dual-color glow.
- Accessibility: keyboard focus visibility, disabled-state styling, and reduced-motion support.

## Design tokens

The palette is a creative direction for this redesign, not a claim about ZOMZEY's official brand colors:

- Obsidian: #090B16
- Ion Cyan: #5EFCE8
- Ultraviolet Prism: #A58BFF
- Digital Blue: #5B7CFF
- Soft White: #F3F6FF
- Warm Signal: #FF8C69

## Structure

The homepage intentionally demonstrates one button at the top-left. The component CSS is isolated in css/components.css; shared values live in css/tokens.css. The hover effect uses CSS only.

## Hosting

Static website deployed by GitHub Pages. No framework, build step, or paid design platform is required.

Future components should be added to this library only after their visuals and interactions have been approved.
