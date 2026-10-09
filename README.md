# ZOMZEY Homepage Redesign

A responsive homepage redesign concept for [zomzey.io](https://zomzey.io/), built with semantic HTML, modular CSS, and vanilla JavaScript.

## Project status

**Phase:** design-system foundation (CP2).  
**Concept direction:** Signal Network (provisional).  
**Note:** this is a work in progress, not the finished contest submission. The palette is a design proposal, not confirmed official brand colors.

## Project documents

- **[PROJECT_BRIEF.md](./PROJECT_BRIEF.md)** — goals, constraints, brand direction, and acceptance criteria.
- **[CONTENT_MAP.md](./CONTENT_MAP.md)** — inventory of current homepage content and proposed hierarchy.
- **[style-guide.html](./style-guide.html)** — live visual reference for color, typography, spacing, shape, and motion tokens.

## Technology

- HTML5 for structure and accessibility.
- CSS for design tokens, layout, reusable components, responsive behavior, and motion.
- Vanilla JavaScript ES modules for interactions that need scripting.
- SVG and optimized image/video assets for lightweight visuals.
- GitHub Pages for static hosting.

GitHub Pages cannot execute PHP or other server-side application logic. Authentication, live member data, payments, and account actions must remain on the real ZOMZEY platform.

## Folder conventions

- `css/tokens.css` — centralized design values and semantic aliases.
- `css/base.css` — reset, typography foundation, and accessible focus behavior.
- `css/layout.css` — shared layout primitives.
- `css/components.css` — reusable product UI components (next phase).
- `css/sections.css` — homepage section compositions.
- `css/responsive.css` — responsive overrides.
- `css/motion.css` — shared motion rules.
- `css/style-guide.css` — only the presentation of the design-system page.
- `js/main.js` and `js/modules/` — modular JavaScript entry point and interactions.
- `assets/images/`, `assets/videos/`, `assets/icons/` — project assets.

Shared visual values belong in design tokens. Add a module or stylesheet only when it has a clear responsibility.

## Local preview

Because browser security can restrict ES modules opened through `file://`, use a local static server or an editor's Live Server extension. Use the deployed GitHub Pages URL for final live QA.

## Deployment

The repository includes a GitHub Actions workflow at `.github/workflows/static.yml` that deploys the repository root when changes reach `main`. Check the **Actions** tab after a push. Do not share the site as a finished contest entry until the homepage, mobile layout, style guide, and interaction notes are complete.

## Working rules

1. Audit before removing existing functionality.
2. Group all checkpoint changes into one commit.
3. Verify design tokens and components before assembling sections.
4. Finish one section at a time, then test desktop and mobile.
5. Use real platform links where a static demo cannot reproduce server-backed features.
6. Never present sample content or simulated metrics as live ZOMZEY data.
