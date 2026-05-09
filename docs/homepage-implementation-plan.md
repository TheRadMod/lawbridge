# Lawbridge Homepage Implementation Plan

## Objective

Create the first public website page for Lawbridge Partners with a professional full-service litigation firm feel.

## Brand Rules

- Use "Lawbridge" as one word.
- Use `logo-effects/lawbridge_logo_glass-frosted-cropped.png` as the homepage header logo; preserve the original frosted source and do not rearrange the bridge, laurel, wordmark, or tagline.
- Use `assets/hero-lawbridge-court.png` as the homepage court-institutional hero image while preserving the original generated source image.
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
    founding partner profile cards by department
  contact section
    Prayagraj, Lucknow, and Delhi addresses
    email and existing mobile numbers only
```

## Prospective Client Conversion Pass

```text
conversion pass
  logo
    create cropped frosted asset from the original square render
    remove outer blank margin while keeping the glass rectangle and immediate shadow
    use the cropped asset in the sticky header
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
    inert View Profile anchors
  contact
    dark structured chambers block
    Prayagraj chambers and Lucknow presence only
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
- [x] Hero asset copied to `assets/hero-lawbridge-court.png` without modifying the generated source image.
- [x] Sticky overflow bug addressed by keeping overflow containment off `html` and `body`.
- [x] Lightweight static verification complete.
- [x] Cropped logo asset created at `logo-effects/lawbridge_logo_glass-frosted-cropped.png`.
- [x] Header updated to use the cropped frosted logo asset with larger intentional placement.
- [x] Prospective-client decision, contact-situation, intake-process, and document-checklist sections added.
- [x] Contact section updated with Prayagraj, Lucknow, and Delhi addresses while omitting landline numbers.
- [ ] Homepage changes committed and pushed.
