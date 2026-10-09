# ZOMZEY Homepage Redesign

A responsive homepage redesign concept for [zomzey.io](https://zomzey.io/), built with semantic HTML, modular CSS, and vanilla JavaScript.

## Project status

**Phase:** discovery and architecture scaffold.  
**Concept direction:** Signal Network (provisional).  
**Note:** this is a work in progress, not the finished contest submission. Final brand colors, typography, composition, and content hierarchy must be validated.

## Project documents

- **PROJECT_BRIEF.md** — goals, constraints, brand direction, and acceptance criteria.
- **CONTENT_MAP.md** — inventory of the current homepage and proposed section order.

## Technology

- HTML5 for structure and accessibility.
- CSS for design tokens, layout, reusable components, responsive behavior, and motion.
- Vanilla JavaScript ES modules for interactions that need scripting.
- SVG and optimized image/video assets for lightweight visuals.
- GitHub Pages for static hosting.

GitHub Pages cannot execute PHP or other server-side application logic. Authentication, live member data, payments, and account actions must remain on the real ZOMZEY platform.

## Folder conventions

- `css/` — stylesheets separated by responsibility.
- `js/main.js` — lightweight entry point.
- `js/modules/` — self-contained interaction modules.
- `assets/images/`, `assets/videos/`, `assets/icons/` — project assets.

Shared visual values belong in design tokens. Add a module or stylesheet only when it has a clear responsibility.

## Local preview

Because browser security can restrict ES modules opened through `file://`, use a local static server or an editor's Live Server extension. Use the deployed GitHub Pages URL for final live QA.

## Deployment

The repository includes a GitHub Actions workflow at `.github/workflows/static.yml` that deploys the repository root when changes reach `main`. Check the **Actions** tab after a push. Do not share the site as a finished contest entry until the homepage, mobile layout, style guide, and interaction notes are complete.

## Working rules

1. Audit before removing existing functionality.
2. Verify shared design tokens and components before assembling sections.
3. Finish one section at a time, then test desktop and mobile.
4. Use real platform links where a static demo cannot reproduce server-backed features.
5. Never present sample content or simulated metrics as live ZOMZEY data.
