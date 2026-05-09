# Lawbridge Brand Design System

## Purpose

This document defines the visual and verbal rules for implementing Lawbridge brand surfaces. It is written for builders, not for presentation only. Use it when creating or reviewing pages, sections, components, images, copy, and responsive behavior.

Approved concept image:

`docs/brand/lawbridge-approved-concept.png`

Current implementation logo:

`logo-effects/lawbridge_logo_glass-frosted.png`

## Brand Positioning

Lawbridge is a serious litigation and advisory firm with a calm institutional presence. The brand should feel precise, research-led, court-ready, and modern without looking like a generic startup or a decorative luxury brand.

The primary impression should be:

- Mature legal judgment.
- High-trust representation.
- Practical clarity for clients.
- Quiet confidence rather than loud promotion.
- Uttar Pradesh court and tribunal depth without provincial styling.

Do not position Lawbridge as a tech product, lead-generation funnel, lifestyle brand, or casual legal directory.

## Naming Rules

Use `Lawbridge` as one word in normal text, with a lowercase `b`.

Preferred:

- Lawbridge
- Lawbridge Partners
- Lawbridge chambers

Do not write:

- Law Bridge
- LawBridge
- Law-bridge
- lawbridge in sentence case unless it appears in a URL, class name, file name, or technical identifier

## Voice and Copy

Voice should be direct, composed, and specific. The writing should sound like a capable legal practice explaining what it does clearly.

Use:

- Short, declarative sentences.
- Practice-specific nouns: litigation, advisory, tribunal, counsel, representation, petitions, appeals, disputes.
- Concrete forums and jurisdictions where relevant.
- Client-facing clarity without oversimplifying legal work.

Avoid:

- Sales-heavy language.
- Startup phrasing such as "seamless", "AI-powered", "scale faster", or "growth engine".
- Overclaims such as "best", "guaranteed", "unmatched", or "winning every case".
- Empty prestige language that does not say what the firm actually does.
- Jokes, informal slogans, emojis, or casual exclamation marks.

Example tone:

`Lawbridge represents clients across litigation, advisory, and tribunal matters with research-led preparation and direct partner involvement.`

## Color System

The current site establishes a strong base palette. Keep it stable unless a future brand review explicitly changes it.

Core tokens:

| Token | Hex | Usage |
| --- | --- | --- |
| Ink | `#111923` | Main text, dark footer, high-authority surfaces |
| Deep blue | `#064f79` | Primary actions, legal authority accent |
| Deep blue dark | `#04344f` | Header links, dark bands, hover states |
| Muted blue | `#2d5f79` | Secondary informational accents |
| Brass | `#d6b44d` | Rules, dividers, high-value highlights |
| Brass soft | `#ead58a` | Dark-surface link accents |
| Maroon | `#6f2636` | Section labels, selective emphasis |
| Stone | `#f7f4ef` | Alternating section background |
| Paper | `#fffdf8` | Main page background |
| Muted text | `#5b6570` | Body copy and secondary text |

Rules:

- Use paper and stone as the primary page backgrounds.
- Use deep blue for primary calls to action and structural brand emphasis.
- Use brass as a restrained accent, mostly for rules, borders, small highlights, and concept references.
- Use maroon sparingly for labels, hover states, and secondary emphasis.
- Keep dark surfaces rare and purposeful, such as footer or high-contrast contact areas.

Do not:

- Turn the site into a single-hue blue interface.
- Use bright neon colors.
- Use generic black and white only.
- Use purple gradients, rainbow gradients, glass orbs, bokeh blobs, or decorative abstract blobs.
- Use brass as a large filled background unless contrast and brand restraint have been reviewed.

## Typography

Current implementation:

- Display serif: `Cormorant Garamond`, fallback `Georgia`, `serif`.
- UI and body sans: `Inter`, fallback `Arial`, `sans-serif`.

Rules:

- Use the serif family for major headings and partner/practice names.
- Use the sans family for navigation, labels, body copy, buttons, metadata, and form controls.
- Keep headings elegant but readable. Large headings should have tight line-height, but text must not overlap.
- Use uppercase tracking only for short labels, navigation items, and button text.
- Body text should stay calm, readable, and not smaller than practical legal-site reading sizes.

Do not:

- Use decorative script fonts.
- Use more than these two type families on primary pages.
- Apply negative letter spacing.
- Scale font size directly with viewport width.
- Use all-caps for long sentences or paragraphs.
- Place oversized hero typography inside cards or cramped panels.

## Layout Rules

The page should feel editorial, structured, and court-institutional. Layouts should use generous whitespace, strong section bands, clean grid systems, and visible hierarchy.

Rules:

- Use full-width sections with constrained internal content.
- Alternate paper and stone backgrounds to create rhythm.
- Prefer grid-based layouts over scattered decorative compositions.
- Keep section headings split from section content where the page needs authority and scanability.
- Use strong horizontal and vertical alignment.
- Leave enough room around the logo and large headings.
- Ensure every section has a clear job: introduce, prove, categorize, profile, or convert.

Do not:

- Put page sections inside floating cards.
- Nest cards inside cards.
- Use landing-page gimmicks such as decorative blobs, oversized icon rows, or animated counters without legal substance.
- Create dense marketing banners that compete with the legal content.
- Add unrelated illustration styles.
- Let text overlap images, borders, buttons, or other content at any viewport size.

## Header Behavior

Current implementation uses a sticky header with:

- Three-column desktop structure: logo, centered navigation, contact action.
- Frosted paper background with blur.
- Brass-tinted bottom border.
- Responsive tablet behavior that hides the contact action.
- Responsive mobile behavior that centers the logo and navigation.

Rules:

- Keep the header sticky unless a page-specific reason is documented.
- Keep the logo visually dominant enough to register as the brand mark.
- Keep navigation labels short and stable.
- Use the header action for a direct contact or chamber inquiry path.
- Maintain readable contrast over the frosted background.
- On mobile, keep the logo and navigation centered and avoid horizontal overflow.

Do not:

- Replace the header logo with live text or reconstructed vector approximations.
- Add multiple primary actions to the header.
- Use a transparent header over busy imagery unless contrast is proven.
- Let navigation wrap into awkward multi-line labels.
- Use hamburger navigation unless the number of links or viewport constraints make it necessary.

## Logo Usage

The logo should remain high fidelity as a single image. The current implementation should use:

`logo-effects/lawbridge_logo_glass-frosted.png`

Rules:

- Treat the logo as artwork, not as editable text.
- Use the PNG as the source of truth for the current site header.
- Preserve aspect ratio.
- Use `object-fit: contain` when sizing the image.
- Provide descriptive alt text such as `Lawbridge Partners`.
- Keep enough clear space around the logo so the glass effect is legible.
- Use the approved concept image as design reference, not as a direct replacement for the header logo unless a future implementation decision says so.

Do not:

- Recreate the logo with text, CSS shadows, emoji, SVG text, or icon fonts.
- Crop the logo.
- Stretch the logo.
- Add new filters, drop shadows, glows, bevels, or blend modes on top of the PNG without review.
- Use low-resolution exports for production.
- Mix multiple logo variants on the same page unless the difference is functional and documented.

## Section Rhythm

Recommended homepage rhythm:

1. Header with logo, primary navigation, and chamber contact action.
2. Hero section with jurisdiction/practice label, large serif statement, concise lede, and two actions at most.
3. Forum or capability strip for quick authority signals.
4. About section with two-column explanatory copy.
5. Practice grid with direct category cards.
6. Partner or department section with structured credentials.
7. Contact section with address and direct contact methods.

Rules:

- Each section should have one dominant message.
- Use labels to orient the reader, not to decorate the page.
- Use practice cards for real service categories only.
- Use list strips for courts, tribunals, and forums where the content benefits from fast scanning.
- Use dark footer/contact areas to close the page with authority.

Do not:

- Add filler sections just to increase page length.
- Repeat the same CTA in every section.
- Use vague section names such as "Solutions" when the content is legal practice.
- Mix unrelated content types in one section.

## Components

### Buttons

Primary buttons:

- Deep blue fill.
- White text.
- Uppercase short label.
- Thin border.
- Small lift or color change on hover.

Secondary buttons:

- Transparent background.
- Deep blue border and text.
- Maroon hover state where appropriate.

Do not:

- Use pill buttons unless the whole design system is intentionally changed.
- Use rounded marketing-style CTAs.
- Use more than two button priorities in one section.
- Use vague labels such as "Learn More" when a precise label is available.

### Cards

Cards are acceptable for repeated items such as practice areas or partner entries.

Rules:

- Keep cards flat or minimally elevated.
- Use borders and grid lines before heavy shadows.
- Keep radius minimal or square.
- Ensure each card has a clear title and useful supporting text.

Do not:

- Use cards for every section.
- Use heavy shadows as the main visual style.
- Add decorative icons unless they are legally meaningful and stylistically restrained.

### Labels

Labels should be short, uppercase, tracked, and used for orientation.

Use labels for:

- About the Firm
- Practice Areas
- Partners
- Contact
- Courts
- Tribunals

Do not use labels as decorative filler or repeat labels so often that they lose meaning.

## Imagery

The approved concept image is the visual reference for atmosphere, composition, and tone. It should guide future art direction: polished, precise, legal, and institutional.

Rules:

- Use imagery that supports legal practice, chambers, documents, court architecture, partners, or institutional credibility.
- Prefer real or high-fidelity generated imagery over generic icons.
- Keep imagery bright enough to inspect and serious enough for a law firm.
- When using partner photographs, preserve professional lighting and natural skin tones.
- Use image crops that show relevant subject matter clearly.

Do not:

- Use generic stock photos of gavels, scales, handshakes, city skylines, or anonymous business people unless specifically approved.
- Use dark blurred backgrounds where the subject cannot be inspected.
- Use AI imagery that visibly distorts legal documents, faces, hands, logos, or text.
- Use ornamental legal symbols as the main brand system.
- Use unrelated abstract gradients as primary imagery.

## Accessibility and Responsiveness

Rules:

- Maintain readable color contrast for all text and buttons.
- Ensure tap targets are large enough on mobile.
- Prevent horizontal overflow on mobile.
- Use real text for content, not text embedded in images except inside the logo artwork.
- Provide alt text for meaningful images.
- Keep focus states visible for keyboard users.

Do not:

- Hide essential information inside hover-only interactions.
- Use low-contrast brass text on paper backgrounds for body copy.
- Depend on animation to communicate required information.
- Allow long legal terms or email addresses to break the mobile layout.

## Prohibited Patterns

Do not use:

- `Law Bridge`, `LawBridge`, or `Law-bridge` in normal text.
- Rebuilt text logos.
- Decorative blobs, bokeh, orbs, or gratuitous gradients.
- Startup SaaS hero language.
- Cartoon legal illustrations.
- Generic scale-of-justice icon systems.
- Oversized cards as page sections.
- Nested cards.
- Heavy glassmorphism across the whole page.
- Multiple competing CTA styles.
- Unreviewed logo effects.
- Cropped or stretched logo assets.
- All-caps paragraphs.
- Low-contrast legal disclaimers or contact details.

## Acceptance Checklist

Before approving a Lawbridge page or component, confirm:

- The brand name is written as `Lawbridge` in normal text.
- The current header logo uses `logo-effects/lawbridge_logo_glass-frosted.png` unless a documented decision says otherwise.
- The logo remains a single high-fidelity image and is not reconstructed in CSS, SVG text, or HTML text.
- The palette stays within the approved ink, blue, brass, maroon, stone, and paper system.
- Typography uses Cormorant Garamond for display and Inter for UI/body text.
- The header remains readable, sticky, and responsive.
- The layout uses full-width sections, clear grids, and restrained cards only where useful.
- Copy is specific to litigation, advisory, courts, tribunals, partners, or contact.
- No generic legal stock tropes dominate the page.
- No decorative blobs, bokeh, orbs, or unrelated gradients are present.
- Mobile views have no horizontal overflow or text collisions.
- Buttons have clear action labels.
- Images have meaningful alt text where applicable.
- The page feels authoritative, calm, and practical rather than promotional or casual.
