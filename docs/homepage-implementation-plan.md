# Lawbridge Homepage Implementation Plan

## Objective

Create the first public website page for Lawbridge Partners with a professional full-service litigation firm feel.

## Brand Rules

- Use "Lawbridge" as one word.
- Use `lawbridge_logo.png` inside a CSS frosted-glass badge for the homepage header logo; preserve the bridge, laurel, wordmark, and tagline.
- Use `assets/allahabad-high-court-hero.png` as the homepage court-institutional hero image while preserving the supplied source image.
- Keep the top navigation visible while scrolling.
- Keep the visual language serious, institutional, and court-facing.

## Implementation Schema

```text
homepage
  sticky header
    exact logo image
    navigation links
    contact button
  hero
    firm name and positioning
    primary action
    secondary action
    court-institutional image layer
  credibility band
    courts and tribunals served
  about section
    boutique litigation firm positioning
    service principles
  practice areas
    compact core service groups
  partners
    silhouetted partner-led representation band
    founding partner profile cards by department
  contact section
    Prayagraj, Lucknow, and Delhi addresses
    email and existing mobile numbers only
```

## Prospective Client Conversion Pass

```text
conversion pass
  logo
    place the transparent source logo inside a rounded CSS frosted-glass badge
    keep the badge large and slightly overlapping the dark masthead
    keep alt text as Lawbridge Partners
  header
    enlarge logo as a square/near-square glass mark
    allow modest overlap below the dark masthead edge
    keep navigation compact and sticky on scroll
  client decision band
    Partner-led departments
    Court and tribunal practice
    Confidential first contact
  when to contact us
    criminal proceedings
    land and civil disputes
    GST and tax notices
    RERA and real estate issues
    company, banking, and recovery matters
    matrimonial disputes with criminal overlap
  after first contact
    conflict and basic review
    documents requested
    senior lawyer evaluation
    forum and strategy discussion
    next-step clarity
  what to send
    order or case number
    notices and pleadings
    timeline and hearing date
    relevant documents
  contact/chambers
    keep Prayagraj address from the firm profile
    add supplied Lucknow and Delhi addresses
    omit landline numbers
    do not invent additional phone numbers
```

## Consolidated Review Correction Pass

```text
correction pass
  hero
    dark legal-blue institutional surface
    court image layer with dark edge blend
    Lawbridge Partners headline
    Advocates & Consultancy label
    brass Contact Chambers action
  header
    sticky dark navy header
    larger single-image logo
    navigation: Home, About Us, Practice Areas, Forums, Partners, Contact
  forums
    paper strip
    semantic list markup
    vertical dividers and restrained glyph slots
  practice areas
    compact icon-led service rows
    brass accents
  partners
    profile-card treatment
    initials placeholders only
    expandable profile previews
  contact
    dark structured chambers block
    expandable city/contact cards
  accessibility
    focus-visible styles
    reduced-motion override
    touch-friendly mobile navigation
    anchor scroll offsets
```

## Status

- [x] Repository initialized and pushed to private GitHub remote.
- [x] Active development branch created: `dev/create-homepage`.
- [x] Source assets preserved.
- [x] Static homepage created.
- [x] Browser rendering verified.
- [x] Consolidated review correction pass applied.
- [x] Earlier generated hero asset preserved at `assets/hero-lawbridge-court.png`.
- [x] Sticky overflow bug addressed by keeping overflow containment off `html` and `body`.
- [x] Lightweight static verification complete.
- [x] Earlier cropped frosted logo asset preserved at `logo-effects/lawbridge_logo_glass-frosted-cropped.png`.
- [x] Header updated to use the transparent source logo inside a CSS frosted-glass badge.
- [x] Prospective-client decision, contact-situation, intake-process, and document-checklist sections added.
- [x] Contact section updated with Prayagraj, Lucknow, and Delhi addresses while omitting landline numbers.
- [x] Allahabad High Court frontage processed into `assets/allahabad-high-court-hero.png`.
- [x] Header logo rebuilt as a rounded frosted-glass badge using the transparent source logo.
- [x] Partner profiles changed to expandable profile previews pending final partner photos/content.
- [x] Contact details changed to expandable city/contact cards.
- [x] Four-partner corridor image added as a dark silhouette trust band.
- [x] Hero image transition softened and chamber-led CTAs restored.
- [ ] Homepage changes committed and pushed.
