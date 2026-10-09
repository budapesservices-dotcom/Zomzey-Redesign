# ZOMZEY UI Library

A lightweight component library for the ZOMZEY homepage redesign. This checkpoint uses a **Clear Signal** direction: a calm light canvas, confident blue primary action, readable labels, and controlled motion. The intention is to be distinctive without relying on decorative effects as a substitute for trust.

## Current component

- Primary action: cobalt blue, white label, firm but modest border radius.
- Interaction: two darker blue striped layers slide in from opposite directions with 300 ms ease-in-out timing.
- Visual feedback: a small lift and restrained shadow. No neon glow or text blend mode.
- Accessibility: keyboard focus visibility, disabled-state styling, and reduced-motion support.
- Label: “Explore opportunities”, consistent with ZOMZEY's marketplace language.

## Provisional design tokens

These are design proposals, not confirmed official ZOMZEY brand colours:

- Ink: #1A2438
- Primary Blue: #3156D8
- Mid Blue: #2849B9
- Deep Blue: #1D367F
- Light Canvas: #F5F7FB
- White: #FFFFFF

## Design rationale

The contest brief asks for a homepage that is modern and unique while still feeling polished and trustworthy. This direction uses clear contrast, predictable interaction feedback, restrained motion, and a credible blue/neutral palette. Brand trust must ultimately come from the whole experience: consistent identity, clear navigation, understandable product value, and honest supporting information.

This repository currently demonstrates the button component only. It is not yet the full contest submission. The separate deliverables still include desktop and mobile homepage mockups, a concise style guide, and notes explaining the layout and interaction cues.

## Structure and hosting

The homepage intentionally demonstrates one button at the top-left. Component CSS is isolated in css/components.css; shared values live in css/tokens.css. The hover effect uses CSS only. GitHub Pages hosts the static preview without a framework or build step.
