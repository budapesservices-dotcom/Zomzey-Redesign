# ZOMZEY Homepage Redesign — Project Brief

**Version:** 0.1  
**Status:** Discovery baseline. Choices marked provisional must be validated before final implementation.  
**Reference:** https://zomzey.io/  
**Contest deliverables:** desktop and mobile mock-ups, concise style guide, and interaction/layout rationale.  
**Implementation:** responsive static front-end hosted by GitHub Pages, using HTML, modular CSS, and vanilla JavaScript.

## 1. Goal

Create a homepage that feels unmistakably modern and original without sacrificing clarity, professionalism, or trust. Avoid the standard “hero, feature blocks, testimonials” template by using a coherent visual idea and intentional content hierarchy.

Visitors should understand what ZOMZEY does, identify their route through the platform, and find a useful next action.

## 2. Product understanding

ZOMZEY presents itself as an opportunity network where people and businesses can find promotional reach, while creators, influencers, shops, communities, venues, musicians, and agencies can discover opportunities to offer services or reach audiences.

The current homepage exposes:
- The positioning “The Opportunity Network.”
- Two main user journeys: “Get a service” and “Give a service.”
- Broad navigation for Pioneers, Influencers, Hubs, Agencies, Pricing, Tools, and supporting resources.
- Directory discovery with search and filters.
- Category links for creators, shops, communities, venues, events, musicians, agencies, bookshops, authors, podcasters, charities, galleries, and more.
- Step-based explanations of the two service journeys.
- A network/map area referring to member locations.
- Member videos/testimonials and a video competition link.
- Use-case links, account access, and footer/support links.
- Tools including influencer pricing and engagement calculators and a campaign-brief generator.

This is a functional inventory, not a requirement to retain the same layout or prominence. Evaluate each item for relevance and placement rather than deleting it only because it complicates the design.

## 3. Core design challenge

The homepage contains many categories, tools, and actions. The redesign should make that breadth feel organized rather than crowded.

Balance:
- **Distinctiveness:** a memorable visual signature, not a generic marketplace template.
- **Clarity:** visitors quickly understand the two main user paths.
- **Discovery:** categories and search remain accessible.
- **Credibility:** visual novelty must not make the platform feel unserious or unsafe.
- **Continuity:** useful routes from the existing platform stay reachable.

## 4. Audiences

### Visitors seeking promotion
People or businesses looking for reach for a product, brand, book, website, event, music, or other offering.

### Visitors offering reach or services
Creators, influencers, shops, communities, venues, musicians, and agencies seeking relevant opportunities.

### Visitors exploring
People who do not yet know which category or path suits them. They need a quick overview and credible examples of use.

## 5. Provisional creative direction: Signal Network

Treat the existing dot-matrix logo as a cue for a visual language built from points, signals, patterns, and connections. The network motif should express meaningful relationships between people and opportunities, not decorative technology for its own sake.

### Provisional palette

These are concept colors, not verified official brand colors:
- Midnight Ink — `#191622`: dark anchor for selected high-impact areas.
- Electric Lime — `#D6FF3F`: main action and attention signal.
- Digital Cobalt — `#665BFF`: secondary accent for connection graphics and selected states.
- Warm Paper — `#F6F4ED`: calm content surface and reading background.
- Signal Coral — `#FF7557`: optional, sparing accent.

Validate this direction against the live site's brand assets and logo behavior before locking tokens. Preserve the provided logo. Ensure contrast is sufficient and never use color alone to convey state.

### Typography and motion

Typography remains undecided. Choose a legible type family and scale after testing real copy at desktop and mobile sizes. Motion should reinforce connection, discovery, and state changes without harming reading. Respect reduced-motion preferences.

## 6. Content and navigation principles

- Keep “Get a service” and “Give a service” clear.
- Simplify the presentation of categories without removing access to important routes.
- Make search and filtering useful rather than visually overwhelming.
- Preserve meaningful paths to pricing, tools, support, account access, and existing resources.
- Consolidate repeated explanations only when it improves comprehension; do not silently remove distinct journeys.
- Link to the real platform when a destination depends on existing ZOMZEY functionality.

## 7. Interaction and technical constraints

- Plan and test desktop, tablet, and mobile layouts.
- Make navigation, steps, filters, and overlays keyboard accessible where applicable.
- Design hover, focus-visible, active, disabled, loading, and error states.
- Do not imply that member listings, map pins, testimonials, or metrics are live unless a verified source is available.
- Demo filtering may use clearly labelled sample data. Authentication, payments, and server-backed profile data must link to ZOMZEY or be explicitly non-functional in the prototype.
- Do not collect or transmit real personal data from the static demo without a deliberately integrated and verified service.
- Keep dependencies low. Start with HTML, CSS, native browser features, SVG, and small ES modules.
- GitHub Pages hosts static content; it does not execute PHP or other server-side application logic.

## 8. Deliverables

1. Desktop homepage.
2. Purpose-designed mobile homepage.
3. Style guide for colors, typography, spacing, buttons, navigation, cards, inputs, and interaction states.
4. Interaction notes explaining important controls and layout choices.
5. Public live prototype, with honest boundaries around backend-dependent functionality.

## 9. Acceptance checklist

- ZOMZEY's purpose and two principal user journeys are clear at first glance.
- The design has a recognizable visual idea related to the existing identity.
- High-value navigation and discovery remain accessible.
- Desktop and mobile are checked for overflow, readability, target sizes, and hierarchy.
- Shared components use consistent design tokens without conflicting CSS implementations.
- JavaScript modules have distinct responsibilities and fail safely if their target elements are absent.
- Keyboard navigation, visible focus, contrast, reduced motion, and semantic HTML are considered.
- Controls behave honestly and links resolve to intentional destinations.
- The live website and contest presentation materials are ready before submission.

## 10. Open decisions

- Final type family and scale.
- Confirmed official brand colors, if any.
- Which sections belong directly on the homepage versus menus/footer.
- Whether reliable and permitted data is available for a live member-location map.
- Which actual videos/images can be used and their performance impact.
- Whether the contest accepts a live URL alongside exported screenshots and written notes.
