# Vectorbross Design System — Style Guide
> **Source:** Figma file `vectorbross-website2026`
> **Last extracted:** March 2026
> **Usage:** Reference for marketing, content, and AI tools across all Vectorbross digital touchpoints.

---

## Table of Contents
1. [Brand Foundations](#1-brand-foundations)
2. [Color System](#2-color-system)
3. [Typography](#3-typography)
4. [Spacing & Layout](#4-spacing--layout)
5. [Border Radius](#5-border-radius)
6. [Shadows & Elevation](#6-shadows--elevation)
7. [Opacity Tokens](#7-opacity-tokens)
8. [Page Templates](#8-page-templates)
9. [Section Components](#9-section-components)
10. [UI Components](#10-ui-components)
11. [For Content Writers & Copywriters](#11-for-content-writers--copywriters)
12. [For Marketers](#12-for-marketers)
13. [For Developers](#13-for-developers)
14. [Quick Reference for AI Prompting](#14-quick-reference-for-ai-prompting)

---

## 1. Brand Foundations

| Token | Value |
|---|---|
| **Primary font (headings)** | Clash Grotesk |
| **Secondary font (body)** | Poppins |
| **Primary brand color** | `#ff3066` |
| **Primary dark / text** | `#1b1a1f` |
| **Background default** | `#ffffff` |
| **Border width** | `1px` |

**Brand personality cues from the system:**
- Large, tight display headings (line-height ≤ 0.9) → bold, confident, editorial
- Light font weights (300) on large headings → modern, clean contrast
- Hot pink primary (`#ff3066`) against near-black (`#1b1a1f`) → high-contrast, energetic

---

## 2. Color System

### 2.1 Brand Primary — Pink/Red Scale

| Token | Hex | Usage |
|---|---|---|
| `Brand/Primary color 1/600` | `#b81c44` | Hover states, pressed, dark accent |
| `Brand/Primary color 1/500` | `#ff3066` | **Main brand color** — CTAs, highlights, links |
| `Brand/Primary color 1/400` | `#fc799b` | Soft accent, decorative |
| `Brand/Primary color 1/300` | `#ffb0c5` | Light tint, backgrounds |
| `Brand/Primary color 1/200` | `#ffd6e1` | Very light tint, hover backgrounds |

### 2.2 Brand Secondary — Dark/Purple Scale

| Token | Hex | Usage |
|---|---|---|
| `Brand/Secondary color 1/700` | `#1b1a1f` | Darkest — backgrounds, primary text |
| `Brand/Secondary color 1/500` | `#343448` | Dark text, secondary backgrounds |
| `Brand/Secondary color 1/400` | `#5e5e80` | Muted text, placeholders |
| `Brand/Secondary color 1/300` | `#bdb4e3` | Soft purple tint |
| `Brand/Secondary color 1/200` | `#ebe7fa` | Very light purple tint |

### 2.3 Neutral Scale

| Token | Hex | Usage |
|---|---|---|
| `Color/Neutral Darkest` | `#1b1a1f` | Primary text, dark backgrounds |
| `Color/Neutral Darker` | `#25252f` | Secondary dark backgrounds |
| `Color/Neutral Dark` | `#343448` | Body text on light backgrounds |
| `Color/Neutral` | `#5e5e80` | Muted / secondary text |
| `Color/Neutral Light` | `#c1bfca` | Borders, dividers, subtle text |
| `Color/Neutral Lighter` | `#cccccc` | Light borders, disabled states |
| `Color/Neutral Lightest` | `#eeeeee` | Light backgrounds, page fill |
| `Color/White` | `#ffffff` | Pure white, card backgrounds |

### 2.4 Semantic / Functional Colors

| Token | Hex | Usage |
|---|---|---|
| `Color/Success` | `#04b56c` | Success messages, confirmations |
| `Color/Error` | `#dc3529` | Error states, destructive actions |
| `Color/Focus` | `#4277f4` | Focus rings, interactive highlight |

### 2.5 Color Scheme 1 — Contextual Mapping

This scheme maps semantic roles to the base palette. Use these tokens when building components or prompting AI tools.

| Role | Token | Hex |
|---|---|---|
| **Background light** | `Color Scheme 1/Background 1` | `#eeeeee` |
| **Background mid** | `Color Scheme 1/Background 2` | `#cccccc` |
| **Background dark** | `Color Scheme 1/Background 4` | `#1b1a1f` |
| **Foreground** | `Color Scheme 1/Foreground` | `#ffffff` |
| **Primary text** | `Color Scheme 1/Text 1` | `#1b1a1f` |
| **Secondary text** | `Color Scheme 1/Text 2` | `#343448` |
| **Muted text** | `Color Scheme 1/Text 3` | `#c1bfca` |
| **Inverted text** | `Color Scheme 1/Text 4` | `#ffffff` |
| **Accent text / highlight** | `Color Scheme 1/Text Color 1` | `#ff3066` |
| **Dark text color** | `Color Scheme 1/Text Color 2` | `#343448` |
| **Medium text color** | `Color Scheme 1/Text Color 3` | `#5e5e80` |
| **Accent** | `Color Scheme 1/Accent` | `#000000` |
| **Border strong** | `Color Scheme 1/Border 1` | `#1b1a1f` |
| **Border soft** | `Color Scheme 1/Border 2` | `#c1bfca` |
| **Border lighter** | `Color Scheme 1/Border 3` | `#cccccc` |
| **Alert focus** | `Color Scheme 1/Alert-focus` | `#4277f4` |
| **Alert success** | `Color Scheme 1/Alert-success` | `#04b56c` |
| **Alert error** | `Color Scheme 1/Alert-error` | `#dc3529` |

---

## 3. Typography

### 3.1 Font Families

| Role | Family | Notes |
|---|---|---|
| **Display / Headings** | `Clash Grotesk` | All H1–H6, Caps, Buttons, Menu labels |
| **Body / UI Text** | `Poppins` | All body sizes (Tiny → Large), Intro Small |

### 3.2 Display Headings — Clash Grotesk

These styles are used for hero sections, section titles, and editorial content.

| Style | Size | Weight | Line Height | Letter Spacing | Token |
|---|---|---|---|---|---|
| **H1 — Homepage** | 90px | 300 Light | 0.80 | −4 | `Heading/H1.Home` |
| **H2 — Homepage** | 70px | 400 Regular | 0.90 | −4 | `Heading/H2.Home` |
| **H1** | 80px | 300 Light | 0.80 | −4 | `Heading/H1` |
| **H2** | 60px | 400 Regular | 0.90 | −4 | `Heading/H2` |
| **H3** | 40px | 400 Regular | 1.10 | −4 | `Heading/H3` |
| **H4** | 30px | 500 Medium | 0.90 | 0 | `Heading/H4` |
| **H5** | 25px | 500 Medium | 1.10 | −2 | `Heading/H5` |
| **H6** | 20px | 500 Medium | 1.10 | −2 | `Heading/H6` |

> ℹ️ Letter spacing values are in Figma units (−4 ≈ −0.04em, −2 ≈ −0.02em).

### 3.3 Intro / Lead Text — Clash Grotesk

Used for introductory paragraphs, callouts, and lead copy.

| Style | Size | Weight | Line Height | Letter Spacing | Token |
|---|---|---|---|---|---|
| **Intro Big** | 30px | 300 Light | 1.20 | −2 | `Intro/Big` |
| **Intro Small** | 20px | 300 Light | 1.20 | −2 | `Intro/Small` |

### 3.4 Body Text — Poppins

All body text uses `line-height: 1.30` and `letter-spacing: −2` unless noted.

#### Body Large — 20px

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Text/Large/Light` |
| Normal | 400 | `Text/Large/Normal` |
| Medium | 500 | `Text/Large/Medium` |
| Semi Bold | 600 | `Text/Large/Semi Bold` |
| Bold | 700 | `Text/Large/Bold` |
| Extra Bold | 800 | `Text/Large/Extra Bold` |
| Link | 500 | `Text/Large/Link` |

#### Body Medium — 18px

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Text/Medium/Light` |
| Normal | 400 | `Text/Medium/Normal` |
| Medium | 500 | `Text/Medium/Medium` |
| Semi Bold | 600 | `Text/Medium/Semi Bold` |
| Bold | 700 | `Text/Medium/Bold` |
| Extra Bold | 800 | `Text/Medium/Extra Bold` |
| Link | 500 | `Text/Medium/Link` |

#### Body Regular — 16px

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Text/Regular/Light` |
| Normal | 400 | `Text/Regular/Normal` |
| Medium | 500 | `Text/Regular/Medium` |
| Semi Bold | 600 | `Text/Regular/Semi Bold` |
| Bold | 700 | `Text/Regular/Bold` |
| Extra Bold | 800 | `Text/Regular/Extra Bold` |
| Link | 500 | `Text/Regular/Link` |

#### Body Small — 14px

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Text/Small/Light` |
| Normal | 400 | `Text/Small/Normal` |
| Medium | 500 | `Text/Small/Medium` |
| Semi Bold | 600 | `Text/Small/Semi Bold` |
| Bold | 700 | `Text/Small/Bold` |
| Extra Bold | 800 | `Text/Small/Extra Bold` |
| Link | 500 | `Text/Small/Link` |

#### Body Tiny — 12px

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Text/Tiny/Light` |
| Normal | 400 | `Text/Tiny/Normal` |
| Medium | 500 | `Text/Tiny/Medium` |
| Semi Bold | 600 | `Text/Tiny/Semi Bold` |
| Bold | 700 | `Text/Tiny/Bold` |
| Extra Bold | 800 | `Text/Tiny/Extra Bold` |
| Link | 500 | `Text/Tiny/Link` |

### 3.5 Caps / Label Text — Clash Grotesk

Used for tags, labels, badges, category indicators. 12px, `line-height: 1.15`, `letter-spacing: 0`.

| Variant | Weight | Token |
|---|---|---|
| Light | 300 | `Caps/Light` |
| Normal | 400 | `Caps/Normal` |
| Medium | 500 | `Caps/Medium` |
| Semi Bold | 600 | `Caps/Semi Bold` |
| Bold | 700 | `Caps/Bold` |
| Extra Bold | 800 | `Caps/Extra Bold` |
| Link | 500 | `Caps/Link` |

### 3.6 Button Text — Clash Grotesk

All button text uses `line-height: 1.15` and `letter-spacing: −2`.

| Style | Size | Weight | Token |
|---|---|---|---|
| Button Large | 16px | 500 Medium | `Buttons/Button Large` |
| Button Large Link | 16px | 500 Medium | `Buttons/Button Large Link` |
| Button Small | 14px | 500 Medium | `Buttons/Button Small` |
| Button Small Link | 14px | 500 Medium | `Buttons/Button Small Link` |

### 3.7 Menu / Navigation Labels — Clash Grotesk

12px, `line-height: 1.50`, `letter-spacing: +2` (spaced, uppercase feel).

| Style | Weight | Token |
|---|---|---|
| Menu On (active) | 400 Regular | `Menu/Menu On` |
| Menu Off (default) | 400 Regular | `Menu/Menu Off` |

---

## 4. Spacing & Layout

### 4.1 Component Padding Tokens

Used for padding inside UI components (cards, buttons, inputs, etc.).

| Token | Value | Usage |
|---|---|---|
| `Paddings/padding-comp-none` | 0px | No padding |
| `Paddings/padding-comp-tiny4` | 4px | Minimal internal gap |
| `Paddings/padding-comp-tiny3` | 8px | Tight padding |
| `Paddings/padding-comp-tiny2` | 12px | Small component padding |
| `Paddings/padding-comp-tiny1` | 16px | Default small padding |
| `Paddings/padding-comp-xxsmall` | 24px | Standard component padding |
| `Paddings/padding-comp-xsmall` | 32px | Comfortable padding |
| `Paddings/padding-comp-medium` | 48px | Medium/generous padding |
| `Paddings/padding-comp-large` | 64px | Large component padding |

### 4.2 Section Padding Tokens

Used for vertical section spacing on the page.

| Token | Value | Usage |
|---|---|---|
| `Paddings/padding-sctn-large` | 112px | Main section top/bottom padding |

### 4.3 General Spacing

| Token | Value |
|---|---|
| `t--spacing/0` | 0px |
| `spacing/3` | 12px |

---

## 5. Border Radius

| Token | Value | Visual feel |
|---|---|---|
| `Radius/radius-none` | 0px | Sharp corners |
| `Radius/radius-tiny` | 2px | Barely rounded |
| `Radius/radius-xxxsmall` | 4px | Very subtle rounding |
| `Radius/radius-xxsmall` | 8px | Subtle — tags, chips |
| `Radius/radius-small` | 16px | Soft — cards, inputs |
| `Radius/radius-medium` | 24px | Rounded — modals, panels |
| `Radius/radius-large` | 32px | Pronounced rounding |
| `Radius/radius-xlarge` | 48px | Strong pill-like feel |
| `Radius/radius-xxlarge` | 64px | Near-circle / pill shapes |

---

## 6. Shadows & Elevation

All shadows are CSS `drop-shadow` / `box-shadow` style. Listed from flattest to most elevated.

| Token | CSS equivalent | Elevation feel |
|---|---|---|
| `xxsmall` | `0 1px 2px rgba(0,0,0,0.05)` | Hairline — subtle card lift |
| `xsmall` | `0 1px 2px rgba(0,0,0,0.06), 0 1px 3px rgba(0,0,0,0.10)` | Very light lift |
| `small` | `0 2px 4px rgba(0,0,0,0.06) -2px, 0 4px 8px rgba(0,0,0,0.10) -2px` | Soft elevation |
| `medium` | `0 4px 6px rgba(0,0,0,0.03) -2px, 0 12px 16px rgba(0,0,0,0.08) -4px` | Floating element |
| `large` | `0 8px 8px rgba(0,0,0,0.03) -4px, 0 20px 24px rgba(0,0,0,0.08) -4px` | Dropdown / popover |
| `xlarge` | `0 24px 48px rgba(0,0,0,0.18) -12px` | Modals, overlays |
| `xxlarge` | `0 32px 64px rgba(0,0,0,0.14) -12px` | Deep focus / hero lift |

---

## 7. Opacity Tokens

| Token | Hex (with alpha) | Value | Usage |
|---|---|---|---|
| `Opacity/Neutral Darkest 30` | `#0000004d` | Black at 30% | Overlays, scrim |
| `Opacity/White 15` | `#ffffff26` | White at 15% | Subtle on dark backgrounds |
| `Opacity/White 30` | `#ffffff4d` | White at 30% | Medium overlay on dark |
| `Opacity/White 50` | `#ffffff80` | White at 50% | Half-transparent white |

---

---

## 8. Page Templates

The Figma file `vectorbross-website2026` contains the following page templates, each designed at **1440px (desktop)** and **440px (mobile)**. All sections within each page are built from reusable section components (see §9).

### 8.1 Desktop Templates (1440px)

| Page | Description | Key sections |
|---|---|---|
| `homepage` | Main landing page | Hero, LB-intro, Cases, Big Quote, Services, CTA, News, USPs, Team, Brands, Stats, FAQs, CTA, Newsletter, Footer |
| `aboutus` | About us overview | Header content, Cases list, USPs, Big Quote, Team, Stats, CTA, Newsletter, Footer |
| `aboutus-detail` | About us detail | Header content, Cases, USPs, Big Quote, Team, Stats, CTA, Newsletter, Footer |
| `services` | Services overview | Header, Service cards, CTA, Newsletter, Footer |
| `service-detail` | Individual service page | Header, Rich text, Related services, CTA, Newsletter, Footer |
| `cases` | Cases / portfolio | Header, Case list (alternating image-text), CTA, Footer |
| `news` | News / blog listing | Header, News cards, Pagination, Newsletter, Footer |
| `news-detail` | Single article | Blog post header, Rich text, Author details, Related news, Newsletter, Footer |
| `team` | Team overview | Header, Team member cards, Stats, CTA, Footer |
| `team-detail` | Individual team member | Header, Bio, Stats, CTA, Newsletter, Footer |
| `careers` | Job listings | Header, Job cards, USPs, CTA, Newsletter, Footer |
| `career-detail` | Individual job post | Header, Job description, Form, CTA, Footer |
| `locations` | Locations overview & detail | Header, Location cards, Map, Contact, Footer |
| `contact` | Contact page | Header, Form (inputs + checkbox + submit), Footer |
| `privacy` | Legal / privacy policy | Header, Rich text, Footer |
| `404` | Error page | Message, CTA, Footer |
| `menu` | Mobile navigation overlay | Menu items with submenu expand/collapse |

### 8.2 Mobile Templates (440px)

All desktop pages have a dedicated **440px mobile counterpart** with the suffix `-mobile` on section components (e.g. `navbar-mobile`, `team-mobile`, `usps-mobile`). Layouts shift from multi-column to single-column stacked.

### 8.3 Homepage Section Order

The canonical section order on the homepage (used as the reference structure):

```
1.  navbar              — 1440 × 76px
2.  Hero                — inline (1440 × 646px)
3.  LB-intro            — inline (1440 × 622px)
4.  cases               — inline (1440 × 1525px)
5.  big-quote           — 1440 × 327px
6.  services            — 1440 × 1945px
7.  Call to Action      — 1440 × 597px
8.  news                — 1440 × 994px
9.  usps                — 1440 × 829px
10. team                — 1440 × 773px
11. brands              — 1440 × 719px
12. stats               — 1440 × 937px
13. faqs                — 1440 × 763px
14. Call to Action      — 1440 × 576px
15. Newsletter section  — 1440 × 368px
16. Footer section      — 1440 × 452px
```

---

## 9. Section Components

These are the full-width reusable sections that compose all pages. Each is a Figma component instance with desktop and mobile variants.

### Layout & Navigation

| Component | Desktop size | Mobile size | Description |
|---|---|---|---|
| `navbar` | 1440 × 76px | `navbar-mobile` 440 × 72px | Top navigation bar with logo, menu links, submenu dropdown |
| `Submenu` | 300 × 212px | — | Desktop dropdown with arrow-icon menu items |
| `menu` (overlay) | — | 440 × 780px | Full-screen mobile menu with collapsible sub-lists |
| `breadcrumb` | 1440 × 54px | 440 × 54px | Breadcrumb trail for inner pages |
| `Footer section` / `Footer Section` | 1440 × 452px | `footer-mobile` 440 × 1131px | Footer with address, contact, social links |

### Hero & Intro Sections

| Component | Desktop size | Mobile size | Description |
|---|---|---|---|
| `Hero` | 1440 × 646px | Stacked in `LB-intro` | Full-width hero with headline, subtext, 2 buttons, image |
| `LB-intro` | 1440 × 622px | 440 × 823px | Intro block: image left + heading + CTA button right |

### Content Sections

| Component | Desktop size | Mobile size | Description |
|---|---|---|---|
| `big-quote` | 1440 × 327px | `big-quote` 440 × 119–151px | Large pull quote / testimonial |
| `services` | 1440 × 1945px | `services-mobile` 440 × 636px | Services grid with title, description, visuals |
| `cases` | 1440 × 1071–1525px | — | Portfolio/cases alternating image-text rows (3 items) |
| `news` | 1440 × 994px | `news` 440 × 760px | Latest news/blog section with cards |
| `usps` | 1440 × 829px | `usps-mobile` 440 × 1501px | USP (unique selling points) icon + text list |
| `team` | 1440 × 773px | `team-mobile` 440 × 565–773px | Team member card grid |
| `brands` | 1440 × 719px | `brands-mobile` 440 × 335px | Logo strip / partner brands |
| `stats` | 1440 × 937px | `stats-mobile` 440 × 415px | Numerical statistics highlights |
| `faqs` | 1440 × 763px | `faqs-mobile` 440 × 804px | FAQ accordion with questions section |
| `rich-text` | 1440px | — | Long-form editorial / article body |
| `slider` | variable | — | Image/content slider |

### Call to Action Sections

| Component | Desktop size | Mobile size | Description |
|---|---|---|---|
| `Call to Action` (large) | 1440 × 597px | `large-cta-mobile` 440 × 634px | Full-width CTA block |
| `small-cta` | variable | `small-cta-mobile` 440 × 609px | Compact CTA variant |
| `Newsletter section` / `newsletter-mobile` | 1440 × 368px | 440 × 307px | Email signup with input + submit button |

### Detail / Inner Page Specific

| Component | Desktop | Mobile | Description |
|---|---|---|---|
| `job-description` / `Job description` | 1440px | — | Job post body with structured fields |
| `card-news` | variable | — | Individual news card (image, date, title, link) |
| `card-location` | variable | — | Location card with address info |

---

## 10. UI Components

These are the atomic-level, reusable UI elements used inside section components.

### 10.1 Button

Figma component: `Button`

| Variant | Size | Font | Notes |
|---|---|---|---|
| Primary (filled) | 154–173 × 48px (large) | Clash Grotesk 16px / 500 | Main CTA action |
| Secondary / outline | ~154 × 48px | Clash Grotesk 16px / 500 | Secondary action |
| Link button | 106 × 18px (small) | Clash Grotesk 14px / 500 | Inline text link with arrow |
| Button Small | ~84–108 × 50px | Clash Grotesk 14px / 500 | Compact variant |

Button text tokens: `Buttons/Button Large`, `Buttons/Button Small`, `Buttons/Button Large Link`, `Buttons/Button Small Link`

### 10.2 Input Field

Figma component: `Input field`

Used on contact and career forms. Paired with `Checkbox` and grouped in `Inputs` / `Form` frames.

| Property | Value |
|---|---|
| Font | Poppins (body) |
| Border | 1px, `Border 1` / `Border 2` |
| Radius | `radius-xxsmall` (8px) or `radius-small` (16px) |
| States | Default, Focus (outline `Color/Focus` `#4277f4`), Error (`Color/Error` `#dc3529`) |

### 10.3 Checkbox

Figma component: `Checkbox`

Used in forms (contact, career application). Standard checkbox with label text in `Text/Small` or `Text/Regular`.

### 10.4 Tag

Figma component: `Tag`

Used for content categorization (news categories, service tags, job types).

| Property | Value |
|---|---|
| Font | `Caps` — Clash Grotesk 12px |
| Radius | `radius-xxsmall` (8px) |
| Padding | `padding-comp-tiny3` (8px) horizontal |

### 10.5 Pagination

Figma component: `Pagination`

Used on news listing and cases pages. Contains numbered pages + prev/next arrows (`Arrow Icon`).

### 10.6 Team Member Card

Figma component: `Team Member Card`

Used in the `team` / `team-mobile` sections.

| Property | Value |
|---|---|
| Image | Rounded rectangle (portrait) |
| Name | `Heading/H5` or `H6` — Clash Grotesk |
| Role | `Text/Small/Normal` — Poppins |
| Radius | `radius-small` (16px) |

### 10.7 Icon

Figma component: `Icon`, `Arrow Icon`

Used throughout for UI feedback (menu arrows, button icons, navigation).

| Property | Value |
|---|---|
| Size | 20 × 20px (Arrow Icon), 30 × 30px (menu icon) |
| Color | Inherits from parent — typically `Color/Neutral Darkest` or `Brand/Primary color 1/500` |

### 10.8 Company Logo

Figma component: `Company Logo`

Used in navbar and footer. Referenced in `brands` section as partner logos.

### 10.9 Banner Questions

Figma component: `banner-questions`

A banner-style section used for FAQ intro or campaign questions. Contains `Questions Section` / `QuestionsSection` frames.

### 10.10 Blog Card

Composed frame: `card-news` / `Blog Card Meta` / `Blog Card Date`

| Element | Token |
|---|---|
| Date label | `Caps` — Clash Grotesk 12px |
| Title | `Heading/H5` or `H6` |
| Body excerpt | `Text/Small/Normal` |
| Link | `Buttons/Button Small Link` |
| Image | Rounded rectangle, `radius-small` (16px) |

---

## 11. For Content Writers & Copywriters

This section translates the design system into practical writing guidelines. Each component has specific copy constraints — respecting them ensures text never breaks layouts.

### 11.1 Text Hierarchy — When to Use What

| Style | Figma token | Typical use | Tone |
|---|---|---|---|
| **H1** (80–90px) | `Heading/H1`, `Heading/H1.Home` | Page title, hero headline | Bold, punchy, max impact — 4 to 8 words |
| **H2** (60–70px) | `Heading/H2`, `Heading/H2.Home` | Section title | Direct, benefit-led — 5 to 10 words |
| **H3** (40px) | `Heading/H3` | Sub-section title, card heading | Descriptive — 6 to 12 words |
| **H4** (30px) | `Heading/H4` | Feature title, intro label | Compact — 4 to 8 words |
| **H5** (25px) | `Heading/H5` | Team name, card title, list title | Short noun phrase — 2 to 5 words |
| **H6** (20px) | `Heading/H6` | Supporting label, small card title | Very short — 2 to 4 words |
| **Intro Big** (30px) | `Intro/Big` | Lead paragraph below H1/H2 | 1 sentence, 15 to 25 words |
| **Intro Small** (20px) | `Intro/Small` | Secondary lead, caption intro | 1 sentence, 10 to 20 words |
| **Body Regular** (16px) | `Text/Regular` | Main body copy | 2 to 5 sentences per block |
| **Body Small** (14px) | `Text/Small` | Supporting text, card body, meta info | 2 to 3 sentences max |
| **Body Tiny** (12px) | `Text/Tiny` | Legal, footnotes, timestamps | Very short, factual |
| **Caps** (12px) | `Caps` | Tags, labels, category badges | ALL CAPS, 1 to 3 words |
| **Button Large** (16px) | `Buttons/Button Large` | Primary CTA | Action verb + object — 2 to 4 words |
| **Button Small** (14px) | `Buttons/Button Small` | Secondary CTA, inline link | 2 to 4 words |
| **Menu label** (12px) | `Menu/Menu On/Off` | Navigation items | 1 to 2 words, title case |

### 11.2 Copy Length by Section Component

| Section | Field | Recommended length |
|---|---|---|
| `Hero` | Headline (H1) | 4–8 words |
| `Hero` | Subtext (Intro Big) | 15–25 words |
| `Hero` | Button labels | 2–4 words each (max 2 buttons) |
| `LB-intro` | Heading (H2–H3) | 5–12 words |
| `LB-intro` | Button label | 2–4 words |
| `big-quote` | Pull quote | 15–30 words — one strong sentence |
| `services` | Service title (H4–H5) | 2–5 words |
| `services` | Service description | 20–40 words |
| `cases` (card) | Case title (H5) | 3–8 words |
| `cases` (card) | Body text | 30–60 words |
| `news` (card) | Article title (H5) | 5–12 words |
| `news` (card) | Excerpt | 20–40 words |
| `usps` | USP title (H5) | 2–5 words |
| `usps` | USP description | 15–30 words |
| `team` (card) | Name (H5–H6) | Full name, 2–3 words |
| `team` (card) | Job title | 2–5 words |
| `stats` | Number / stat | 1 value + unit (e.g. "250+", "12 years") |
| `stats` | Stat label | 2–5 words |
| `faqs` | Question | 5–12 words, ends with "?" |
| `faqs` | Answer | 30–80 words |
| `Call to Action` | Headline | 5–10 words |
| `Call to Action` | Body | 15–30 words |
| `Call to Action` | Button | 2–4 words |
| `Newsletter section` | Headline | 4–8 words |
| `Newsletter section` | Subtext | 10–20 words |
| `Footer` | Address block | Street, city, country — 1–2 lines |
| `Footer` | Tagline / description | 10–20 words |

### 11.3 Writing Tone & Voice

Based on the design system's visual language (high contrast, tight headings, editorial feel), copy should follow these principles:

**Be direct.** Headings are tight and punchy. No filler words. Lead with the benefit or the action.

**Use active voice.** "We build digital experiences" not "Digital experiences are built by us."

**Keep it confident.** The brand color is hot pink — the writing should match: bold, clear, no hedging.

**Short sentences win.** Especially in Intro and Body styles. One idea per sentence.

**CTAs are verbs.** "Discover our work", "Talk to us", "Read the case" — always action-first.

**Caps/Tags are labels, not sentences.** "BRANDING", "UX DESIGN", "NEWS" — no verbs, no articles.

### 11.4 Punctuation & Formatting Rules

- **Headlines**: No period at the end. Sentence case (only first word capitalized unless proper noun).
- **Tags / Caps labels**: ALL CAPS. No punctuation.
- **CTAs**: No period. Capitalize first word only (e.g. "Read more", not "Read More").
- **Body text**: Normal punctuation. Avoid exclamation marks unless clearly editorial.
- **Pull quotes**: Can use em-dashes (—) for attribution. No quotation marks in the Figma design — add them only if confirmed by brand guidelines.

---

## 12. For Marketers

### 12.1 Approved Color Combinations

These pairings are validated by the design system. Use them for campaign assets, social media, emails, and presentations.

| Use case | Background | Text / Foreground | Accent |
|---|---|---|---|
| **Hero / Impact** | `#1b1a1f` (near-black) | `#ffffff` (white) | `#ff3066` (pink) |
| **Standard page** | `#ffffff` (white) | `#1b1a1f` (near-black) | `#ff3066` (pink) |
| **Light section** | `#eeeeee` (light grey) | `#1b1a1f` (near-black) | `#ff3066` (pink) |
| **Card / panel** | `#ffffff` (white) | `#343448` (dark navy) | `#ff3066` (pink) |
| **CTA block** | `#ff3066` (pink) | `#ffffff` (white) | `#1b1a1f` (near-black) |
| **Alert / badge** | `#ff3066` (pink) | `#ffffff` (white) | — |
| **Success state** | `#04b56c` (green) | `#ffffff` (white) | — |
| **Error state** | `#dc3529` (red) | `#ffffff` (white) | — |
| **Muted / subtle** | `#eeeeee` (light grey) | `#5e5e80` (grey-purple) | — |

> ⚠️ Never place `#ff3066` text directly on `#eeeeee` backgrounds — contrast is insufficient for body text. Use it only for large display text or icons on light backgrounds.

### 12.2 Brand Color Quick Reference

| Color | Hex | Name to use in briefs |
|---|---|---|
| Brand pink | `#ff3066` | "Vectorbross Pink" / "Brand Red" |
| Near-black | `#1b1a1f` | "Vectorbross Black" |
| Dark navy | `#343448` | "Brand Dark" |
| Grey-purple | `#5e5e80` | "Brand Muted" |
| Light grey | `#eeeeee` | "Background Grey" |
| White | `#ffffff` | "White" |

### 12.3 Do's and Don'ts

**DO:**
- Use `#ff3066` for a single focal point per visual — CTA button, one headline word, an icon
- Use near-black backgrounds (`#1b1a1f`) for high-impact, editorial sections
- Pair Clash Grotesk display headings with generous white space
- Keep button labels short (2–4 words) and action-oriented
- Use the light grey background (`#eeeeee`) to break up all-white page sections

**DON'T:**
- Don't use more than 2 font families — only Clash Grotesk and Poppins
- Don't use `#ff3066` as a large background color outside of dedicated CTA blocks
- Don't mix border-radius values within a single component (pick one level from the scale)
- Don't add drop shadows heavier than `medium` to inline elements or text
- Don't use more than 2 CTA buttons per section — the design only supports 2
- Don't use font weights above 500 (Medium) for Clash Grotesk headings — the design uses Light (300) and Regular (400) for large display text

### 12.4 Asset Specifications by Channel

| Channel | Safe dimensions | Background | Font notes |
|---|---|---|---|
| **Website hero** | 1440 × 646px (desktop) / 440 × 646px (mobile) | `#ffffff` or `#1b1a1f` | H1 Home: Clash Grotesk 90px / 300 |
| **Website card** | 605 × 340–360px (desktop) / 400 × 360px (mobile) | `#eeeeee` | H5: Clash Grotesk 25px |
| **Social — square** | 1080 × 1080px | `#1b1a1f` or `#ff3066` | Clash Grotesk, tight line-height |
| **Social — story** | 1080 × 1920px | `#1b1a1f` | Large H1-style headline |
| **Email header** | 600px wide | `#ffffff` | Poppins for body, Clash Grotesk for subject line |
| **Newsletter section** | 1440 × 368px | `#eeeeee` or `#1b1a1f` | H4 + Body Regular |

### 12.5 Campaign Checklist

Before sending any asset to production, verify:

- [ ] Only `Clash Grotesk` and `Poppins` fonts used
- [ ] Primary pink `#ff3066` used sparingly (max 1–2 focal points per visual)
- [ ] CTA button text is 2–4 words, action-first
- [ ] Headline is ≤10 words
- [ ] Image radius matches the scale (8px, 16px, or 24px — no custom values)
- [ ] No more than 2 buttons per section
- [ ] Color combination is from the approved pairings (§12.1)
- [ ] Body text is Poppins, not Clash Grotesk

---

## 13. For Developers

### 13.1 CSS Custom Properties

Paste this block into your project's `:root` stylesheet to use all design tokens as CSS variables.

```css
:root {
  /* ── Brand Colors ──────────────────────────────── */
  --color-brand-600:          #b81c44;
  --color-brand-500:          #ff3066;   /* primary */
  --color-brand-400:          #fc799b;
  --color-brand-300:          #ffb0c5;
  --color-brand-200:          #ffd6e1;

  /* ── Secondary / Dark Scale ────────────────────── */
  --color-secondary-700:      #1b1a1f;
  --color-secondary-500:      #343448;
  --color-secondary-400:      #5e5e80;
  --color-secondary-300:      #bdb4e3;
  --color-secondary-200:      #ebe7fa;

  /* ── Neutrals ───────────────────────────────────── */
  --color-neutral-darkest:    #1b1a1f;
  --color-neutral-darker:     #25252f;
  --color-neutral-dark:       #343448;
  --color-neutral:            #5e5e80;
  --color-neutral-light:      #c1bfca;
  --color-neutral-lighter:    #cccccc;
  --color-neutral-lightest:   #eeeeee;
  --color-white:              #ffffff;

  /* ── Semantic ───────────────────────────────────── */
  --color-success:            #04b56c;
  --color-error:              #dc3529;
  --color-focus:              #4277f4;

  /* ── Opacity ────────────────────────────────────── */
  --color-black-30:           rgba(0, 0, 0, 0.30);
  --color-white-15:           rgba(255, 255, 255, 0.15);
  --color-white-30:           rgba(255, 255, 255, 0.30);
  --color-white-50:           rgba(255, 255, 255, 0.50);

  /* ── Typography ─────────────────────────────────── */
  --font-heading:             'Clash Grotesk', sans-serif;
  --font-body:                'Poppins', sans-serif;

  --text-h1-home:             90px;
  --text-h2-home:             70px;
  --text-h1:                  80px;
  --text-h2:                  60px;
  --text-h3:                  40px;
  --text-h4:                  30px;
  --text-h5:                  25px;
  --text-h6:                  20px;
  --text-intro-big:           30px;
  --text-intro-small:         20px;
  --text-body-large:          20px;
  --text-body-medium:         18px;
  --text-body-regular:        16px;
  --text-body-small:          14px;
  --text-body-tiny:           12px;
  --text-caps:                12px;
  --text-button-large:        16px;
  --text-button-small:        14px;
  --text-menu:                12px;

  /* ── Spacing / Padding ──────────────────────────── */
  --space-0:                  0px;
  --space-4:                  4px;
  --space-8:                  8px;
  --space-12:                 12px;
  --space-16:                 16px;
  --space-24:                 24px;
  --space-32:                 32px;
  --space-48:                 48px;
  --space-64:                 64px;
  --space-section:            112px;

  /* ── Border Radius ──────────────────────────────── */
  --radius-none:              0px;
  --radius-tiny:              2px;
  --radius-xxxsmall:          4px;
  --radius-xxsmall:           8px;
  --radius-small:             16px;
  --radius-medium:            24px;
  --radius-large:             32px;
  --radius-xlarge:            48px;
  --radius-xxlarge:           64px;

  /* ── Shadows ─────────────────────────────────────── */
  --shadow-xxsmall:           0 1px 2px rgba(0,0,0,0.05);
  --shadow-xsmall:            0 1px 2px rgba(0,0,0,0.06), 0 1px 3px rgba(0,0,0,0.10);
  --shadow-small:             0 2px 4px rgba(0,0,0,0.06), 0 4px 8px rgba(0,0,0,0.10);
  --shadow-medium:            0 4px 6px rgba(0,0,0,0.03), 0 12px 16px rgba(0,0,0,0.08);
  --shadow-large:             0 8px 8px rgba(0,0,0,0.03), 0 20px 24px rgba(0,0,0,0.08);
  --shadow-xlarge:            0 24px 48px rgba(0,0,0,0.18);
  --shadow-xxlarge:           0 32px 64px rgba(0,0,0,0.14);

  /* ── Layout ─────────────────────────────────────── */
  --breakpoint-desktop:       1440px;
  --breakpoint-mobile:        440px;
  --layout-content-width:     1120px;
  --layout-gutter:            160px;   /* (1440 - 1120) / 2 */
  --border-width:             1px;
}
```

### 13.2 Breakpoints

| Name | Width | Context |
|---|---|---|
| Desktop | `1440px` | All full-width section components |
| Mobile | `440px` | All `-mobile` component variants |
| Content column | `1120px` | Inner content max-width on desktop |
| Side gutter | `160px` | Left/right padding on desktop (`80px` each side seen in Hero) |

```css
/* Desktop first */
@media (max-width: 440px) {
  /* mobile styles */
}

/* Or mobile first */
@media (min-width: 441px) {
  /* desktop styles */
}
```

### 13.3 Typography CSS Classes

```css
/* Display Headings — Clash Grotesk */
.h1-home  { font-family: var(--font-heading); font-size: var(--text-h1-home); font-weight: 300; line-height: 0.80; letter-spacing: -0.04em; }
.h2-home  { font-family: var(--font-heading); font-size: var(--text-h2-home); font-weight: 400; line-height: 0.90; letter-spacing: -0.04em; }
.h1       { font-family: var(--font-heading); font-size: var(--text-h1);      font-weight: 300; line-height: 0.80; letter-spacing: -0.04em; }
.h2       { font-family: var(--font-heading); font-size: var(--text-h2);      font-weight: 400; line-height: 0.90; letter-spacing: -0.04em; }
.h3       { font-family: var(--font-heading); font-size: var(--text-h3);      font-weight: 400; line-height: 1.10; letter-spacing: -0.04em; }
.h4       { font-family: var(--font-heading); font-size: var(--text-h4);      font-weight: 500; line-height: 0.90; letter-spacing: 0; }
.h5       { font-family: var(--font-heading); font-size: var(--text-h5);      font-weight: 500; line-height: 1.10; letter-spacing: -0.02em; }
.h6       { font-family: var(--font-heading); font-size: var(--text-h6);      font-weight: 500; line-height: 1.10; letter-spacing: -0.02em; }

/* Intro — Clash Grotesk */
.intro-big   { font-family: var(--font-heading); font-size: var(--text-intro-big);   font-weight: 300; line-height: 1.20; letter-spacing: -0.02em; }
.intro-small { font-family: var(--font-heading); font-size: var(--text-intro-small); font-weight: 300; line-height: 1.20; letter-spacing: -0.02em; }

/* Body — Poppins */
.body-large   { font-family: var(--font-body); font-size: var(--text-body-large);   font-weight: 400; line-height: 1.30; letter-spacing: -0.02em; }
.body-medium  { font-family: var(--font-body); font-size: var(--text-body-medium);  font-weight: 400; line-height: 1.30; letter-spacing: -0.02em; }
.body-regular { font-family: var(--font-body); font-size: var(--text-body-regular); font-weight: 400; line-height: 1.30; letter-spacing: -0.02em; }
.body-small   { font-family: var(--font-body); font-size: var(--text-body-small);   font-weight: 400; line-height: 1.30; letter-spacing: -0.02em; }
.body-tiny    { font-family: var(--font-body); font-size: var(--text-body-tiny);    font-weight: 400; line-height: 1.30; letter-spacing: -0.02em; }

/* Caps — Clash Grotesk */
.caps { font-family: var(--font-heading); font-size: var(--text-caps); font-weight: 400; line-height: 1.15; letter-spacing: 0; text-transform: uppercase; }

/* Buttons — Clash Grotesk */
.btn-large { font-family: var(--font-heading); font-size: var(--text-button-large); font-weight: 500; line-height: 1.15; letter-spacing: -0.02em; }
.btn-small { font-family: var(--font-heading); font-size: var(--text-button-small); font-weight: 500; line-height: 1.15; letter-spacing: -0.02em; }

/* Menu — Clash Grotesk */
.menu-label { font-family: var(--font-heading); font-size: var(--text-menu); font-weight: 400; line-height: 1.50; letter-spacing: 0.02em; }
```

### 13.4 Component Token Map

Quick reference mapping Figma component names to their CSS token usage:

| Component | Key tokens |
|---|---|
| `Button` (primary) | `--color-brand-500` bg, `--color-white` text, `--radius-small`, `--btn-large` |
| `Button` (hover) | `--color-brand-600` bg |
| `Input field` | `--border-width` border, `--color-neutral-light` border-color, `--radius-xxsmall`, `--body-regular` |
| `Input field` (focus) | `--color-focus` outline |
| `Input field` (error) | `--color-error` border + message |
| `Tag` | `--color-neutral-lightest` bg, `--caps`, `--radius-xxsmall`, `--space-8` padding |
| `Team Member Card` | `--radius-small` image, `--shadow-small`, `--h5` name, `--body-small` role |
| `navbar` | `--color-white` bg, `--color-neutral-darkest` text, `--shadow-xxsmall` |
| Section padding | `--space-section` top/bottom, `--layout-content-width` max-width |

---

## 14. Quick Reference for AI Prompting

Use this section to prompt any AI tool (Claude, ChatGPT, Midjourney, DALL·E, Figma AI, etc.) and get outputs that stay on-brand. Copy-paste the relevant block directly into your prompt.

---

### 14.1 Universal Brand Context Block

Paste this at the start of any AI prompt when you need brand-consistent output:

```
You are working with the Vectorbross brand. Apply these design system rules strictly:

COLORS:
- Primary brand: #ff3066 (hot pink) — use sparingly, max 1–2 focal points
- Background options: #ffffff (white), #eeeeee (light grey), #1b1a1f (near-black)
- Body text: #1b1a1f (near-black) on light, #ffffff on dark
- Muted text: #5e5e80
- Success: #04b56c | Error: #dc3529 | Focus: #4277f4

TYPOGRAPHY:
- Headings: Clash Grotesk — tight, Light/Regular weight, line-height 0.80–1.10
- Body: Poppins — Regular 400, line-height 1.30
- Labels/Tags: Clash Grotesk 12px, uppercase

TONE: Bold, direct, editorial. Short sentences. Active voice. Action-first CTAs.
STYLE: High-contrast, modern, clean. No decorative flourishes.
```

---

### 14.2 Prompts for Copywriting (Claude / ChatGPT)

**Write a Hero section:**
```
Write a hero section for the Vectorbross website.
Headline: max 8 words, Clash Grotesk style (punchy, confident, no period).
Subtext (Intro Big): 1 sentence, 15–25 words, benefit-led.
2 CTA buttons: action verbs, 2–4 words each.
Tone: bold, direct, high-contrast editorial. No filler words.
Context: [describe the page topic here]
```

**Write a Services section:**
```
Write 3–5 service descriptions for Vectorbross.
Each service: title (2–5 words, H4 style) + description (20–40 words, Poppins body tone).
Tone: confident, professional, benefit-led. No buzzwords.
Services to describe: [list them here]
```

**Write a Big Quote / Pull Quote:**
```
Write a pull quote (testimonial or brand statement) for Vectorbross.
Length: 15–30 words, one powerful sentence.
Style: editorial, impactful. Can use an em-dash for attribution.
Topic/context: [describe here]
```

**Write FAQ items:**
```
Write [N] FAQ items for Vectorbross, topic: [topic].
Format: Question (5–12 words, ends with ?) + Answer (30–80 words, Poppins body tone).
Tone: clear, reassuring, direct. No corporate jargon.
```

**Write a CTA section:**
```
Write a Call to Action section for Vectorbross.
Headline: 5–10 words, punchy.
Body: 15–30 words, builds urgency or desire.
Button label: 2–4 words, action-first (e.g. "Start your project").
Context: [what action should the visitor take?]
```

---

### 14.3 Prompts for Image Generation (Midjourney / DALL·E / Firefly)

**Brand photography style:**
```
Professional brand photography for a digital agency called Vectorbross.
Color palette: near-black #1b1a1f, hot pink accent #ff3066, clean white.
Style: editorial, high-contrast, modern. Clean backgrounds.
No stock photo feel. Confident, bold compositions.
[Describe specific subject here]
--ar 16:9 --style raw
```

**Hero image:**
```
Hero background image for a digital agency website.
Mood: bold, editorial, high-contrast. Dark tones with pink accent highlights.
Colors: #1b1a1f background, #ff3066 accent, white highlights.
No people. Abstract or architectural. Clean, modern.
Aspect ratio: 3:2 (608×486px area)
```

**Team member card photo:**
```
Professional portrait photo for a digital agency team card.
Background: neutral light grey #eeeeee or dark #1b1a1f.
Style: editorial, confident, clean. Soft lighting.
Aspect ratio: portrait (400×360px).
```

**Social media post — square:**
```
Social media graphic (1080×1080px) for Vectorbross digital agency.
Brand colors: #1b1a1f background, #ff3066 accent, #ffffff text.
Typography: bold, tight, editorial (Clash Grotesk style).
Style: minimal, high-contrast, modern.
Content: [headline or message here]
```

---

### 14.4 Prompts for UI / Component Generation (v0, Figma AI, Copilot)

**Generate a Button component:**
```
Create a button component using this design system:
- Large: 48px height, Clash Grotesk 16px Medium (500), padding 24px horizontal
- Primary: background #ff3066, text #ffffff, radius 16px
- Hover: background #b81c44
- Secondary: border 1px #1b1a1f, text #1b1a1f, background transparent
- Focus: outline 2px #4277f4
- Small variant: 14px font, ~40px height
```

**Generate a Card component:**
```
Create a card component (news/case card):
- Image: rounded corners radius 16px (--radius-small), aspect ratio 16:9
- Title: Clash Grotesk 25px Medium (500), color #1b1a1f, max 2 lines
- Body text: Poppins 14px Regular, color #343448, max 3 lines (60 words)
- Link/CTA: Clash Grotesk 14px Medium, color #ff3066, no underline default
- Card background: #ffffff, shadow: 0 4px 6px rgba(0,0,0,0.03), 0 12px 16px rgba(0,0,0,0.08)
- Border radius: 16px
```

**Generate a Form (input + checkbox):**
```
Create a contact form using this design system:
- Input field: Poppins 16px, border 1px #c1bfca, radius 8px, padding 12px 16px
- Input focus: border-color #4277f4, outline 2px #4277f4
- Input error: border-color #dc3529
- Placeholder: color #5e5e80
- Checkbox: custom styled, accent color #ff3066
- Submit button: Primary button style (see Button spec above)
```

---

### 14.5 Prompts for Presentation / Document AI (Claude, Copilot, Notion AI)

**Create a page outline:**
```
Create a content outline for a [page type: services/cases/team/contact] page
following the Vectorbross website structure:
- navbar
- breadcrumb (if inner page)
- header section: headline (H2, 5–10 words) + lead text (Intro Big, 15–25 words)
- [main content sections]
- Call to Action: headline + body + button
- Newsletter signup
- Footer
For each section, suggest: headline, body copy length, and CTA if applicable.
Topic/context: [describe here]
```

---

### 14.6 Token Summary Cheatsheet

```
COLORS ─────────────────────────────────────────────
Brand pink:        #ff3066    Brand dark:       #b81c44
Near-black:        #1b1a1f    Dark navy:        #343448
Grey-purple:       #5e5e80    Light grey:       #eeeeee
White:             #ffffff    Success:          #04b56c
Error:             #dc3529    Focus:            #4277f4

TYPOGRAPHY ─────────────────────────────────────────
Heading font:   Clash Grotesk    Body font: Poppins
H1 home: 90px/300/lh0.80    H1: 80px/300/lh0.80
H2 home: 70px/400/lh0.90    H2: 60px/400/lh0.90
H3: 40px/400/lh1.10         H4: 30px/500/lh0.90
H5: 25px/500/lh1.10         H6: 20px/500/lh1.10
Intro Big: 30px/300/lh1.20  Body: 16px/400/lh1.30
Caps: 12px/400/UC           Button L: 16px/500
Menu: 12px/400/ls+2

SPACING ────────────────────────────────────────────
4 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 112px (section)

RADIUS ─────────────────────────────────────────────
0 / 2 / 4 / 8 / 16 / 24 / 32 / 48 / 64px

LAYOUT ─────────────────────────────────────────────
Desktop: 1440px   Mobile: 440px   Content: 1120px
```

---

*This document was auto-generated from Figma variables and component data. Sources: node `10202-2` (variables) + node `14227-12395` (components & pages). To update, re-run the Figma extraction on the `vectorbross-website2026` file.*
