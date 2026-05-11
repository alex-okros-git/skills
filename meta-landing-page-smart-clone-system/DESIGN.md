---
version: "alpha"
name: "Brico Depot"
description: "Brico Depot design system for landing pages and web interfaces. A bold, utilitarian aesthetic built on the signature Brico Depot red, charcoal neutrals, and an 8px spacing grid. Designed for clarity, trust, and conversion across product-driven retail experiences. Supports light and dark modes."
colors:
  primary: "#E30612"
  primary-hover: "#B0050E"
  primary-light: "#FCECED"
  secondary: "#323232"
  tertiary: "#757575"
  neutral: "#F4F4F6"
  background: "#FFFFFF"
  surface: "#F4F4F6"
  text-primary: "#323232"
  text-secondary: "#757575"
  text-inverse: "#FFFFFF"
  border: "#E0E0E2"
  disabled: "#BDBDBD"
  success: "#1B873F"
  warning: "#E5A000"
  error: "#E30612"
  dark:
    background: "#1A1A1A"
    surface: "#2A2A2A"
    text-primary: "#F0F0F2"
    text-secondary: "#A0A0A0"
    text-inverse: "#1A1A1A"
    primary: "#F04048"
    primary-hover: "#E30612"
    border: "#3A3A3A"
    disabled: "#555555"
    success: "#34D058"
    warning: "#F0B429"
    error: "#F04048"
typography:
  display:
    fontFamily: "Inter, SF Pro Display, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif"
    fontSize: "48px"
    fontWeight: 700
    lineHeight: "1.2"
    letterSpacing: "-0.03em"
  h1:
    fontFamily: "Inter"
    fontSize: "32px"
    fontWeight: 700
    lineHeight: "1.2"
    letterSpacing: "-0.02em"
  h2:
    fontFamily: "Inter"
    fontSize: "24px"
    fontWeight: 700
    lineHeight: "1.2"
    letterSpacing: "-0.01em"
  h3:
    fontFamily: "Inter"
    fontSize: "20px"
    fontWeight: 600
    lineHeight: "1.2"
    letterSpacing: "-0.01em"
  h4:
    fontFamily: "Inter"
    fontSize: "18px"
    fontWeight: 600
    lineHeight: "1.5"
  body-lg:
    fontFamily: "Inter"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: "1.7"
  body:
    fontFamily: "Inter"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "1.5"
  body-sm:
    fontFamily: "Inter"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "1.5"
  caption:
    fontFamily: "Inter"
    fontSize: "12px"
    fontWeight: 500
    lineHeight: "1.5"
    letterSpacing: "0.01em"
  overline:
    fontFamily: "Inter"
    fontSize: "11px"
    fontWeight: 600
    lineHeight: "1.5"
    letterSpacing: "0.08em"
    textTransform: "uppercase"
  mono:
    fontFamily: "SF Mono, Fira Code, Cascadia Code, monospace"
rounded:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "16px"
  xl: "24px"
  full: "9999px"
spacing:
  base: "8px"
  1: "4px"
  2: "8px"
  3: "12px"
  4: "16px"
  5: "24px"
  6: "32px"
  7: "40px"
  8: "48px"
  9: "56px"
  10: "64px"
shadows:
  xs: "0 1px 2px rgba(0,0,0,0.05)"
  sm: "0 2px 4px rgba(0,0,0,0.08)"
  md: "0 4px 12px rgba(0,0,0,0.10)"
  lg: "0 8px 24px rgba(0,0,0,0.12)"
  xl: "0 16px 48px rgba(0,0,0,0.16)"
  dark:
    xs: "0 1px 2px rgba(0,0,0,0.20)"
    sm: "0 2px 4px rgba(0,0,0,0.25)"
    md: "0 4px 12px rgba(0,0,0,0.30)"
    lg: "0 8px 24px rgba(0,0,0,0.35)"
    xl: "0 16px 48px rgba(0,0,0,0.45)"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    hoverBackgroundColor: "{colors.primary-hover}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body}"
    fontWeight: 600
    rounded: "{rounded.sm}"
    padding: "12px 24px"
  button-primary-sm:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-sm}"
    fontWeight: 600
    rounded: "{rounded.xs}"
    padding: "8px 16px"
  button-primary-lg:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body-lg}"
    fontWeight: 600
    rounded: "{rounded.md}"
    padding: "16px 32px"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body}"
    fontWeight: 600
    rounded: "{rounded.sm}"
    padding: "12px 24px"
    border: "1px solid {colors.border}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    typography: "{typography.body}"
    fontWeight: 600
    rounded: "{rounded.sm}"
    padding: "12px 24px"
  button-destructive:
    backgroundColor: "{colors.error}"
    textColor: "{colors.text-inverse}"
    typography: "{typography.body}"
    fontWeight: 600
    rounded: "{rounded.sm}"
    padding: "12px 24px"
  card-default:
    backgroundColor: "{colors.background}"
    border: "1px solid {colors.border}"
    rounded: "{rounded.md}"
    padding: "24px"
    shadow: "{shadows.sm}"
    hoverShadow: "{shadows.md}"
  card-elevated:
    backgroundColor: "{colors.background}"
    border: "none"
    rounded: "{rounded.md}"
    padding: "24px"
    shadow: "{shadows.lg}"
    hoverShadow: "{shadows.xl}"
  input:
    backgroundColor: "{colors.background}"
    textColor: "{colors.text-primary}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: "12px 16px"
    border: "1px solid {colors.border}"
    focusBorderColor: "{colors.primary}"
    focusRing: "0 0 0 3px rgba(227,6,18,0.12)"
    errorBorderColor: "{colors.error}"
    errorFocusRing: "0 0 0 3px rgba(227,6,18,0.18)"
    placeholderColor: "{colors.disabled}"
---



---

👇 Delete the following lines when building your DESIGN.md file (this one included):

We adapted the [design system outcome](../design-system-when-you-have-no-designers-around/design-system.html) (colors, typography, spacing, components etc.) from the default prompt for design-system.md file

👆 Delete the lines above when building your DESIGN.md file (this one included)

---

## Overview

Brico Depot is a leading home improvement and building materials retailer. This design system defines the visual language for Brico Depot landing pages and web interfaces — optimised for product discovery, promotional clarity, and high-conversion retail flows.

- **Composition cues:**
  - Layout: Grid-based, structured for product grids and promotional blocks
  - Content Width: Full Bleed hero sections with contained content areas
  - Framing: Controlled, utilitarian — form follows function
  - Grid: Strong 8px spatial rhythm

- **Brand personality:** Practical, trustworthy, bold. The signature red conveys urgency and energy; charcoal and light grey ground the interface in workmanlike clarity.

## Colors

The color system is anchored by Brico Depot red (#E30612), paired with charcoal (#323232) for text and light grey (#F4F4F6) for surfaces. Full light and dark mode support is included.

- **Primary (#E30612):** Signature Brico Depot red — used for CTAs, active states, price highlights, and primary emphasis.
- **Primary Hover (#B0050E):** Darkened red for interactive hover and pressed states.
- **Primary Light (#FCECED):** Tinted background for banners, alerts, and subtle red highlights.
- **Secondary (#323232):** Charcoal — primary text, headings, and high-contrast elements.
- **Tertiary (#757575):** Mid-grey — secondary text, captions, metadata, and supporting content.
- **Neutral (#F4F4F6):** Light grey — surfaces, cards, input backgrounds, and section dividers.

- **Semantic colors:**
  - Background: #FFFFFF (light) / #1A1A1A (dark)
  - Surface: #F4F4F6 (light) / #2A2A2A (dark)
  - Text Primary: #323232 (light) / #F0F0F2 (dark)
  - Text Secondary: #757575 (light) / #A0A0A0 (dark)
  - Border: #E0E0E2 (light) / #3A3A3A (dark)
  - Disabled: #BDBDBD (light) / #555555 (dark)
  - Success: #1B873F (light) / #34D058 (dark)
  - Warning: #E5A000 (light) / #F0B429 (dark)
  - Error: #E30612 (light) / #F04048 (dark)

## Typography

Typography uses Inter as the single sans-serif family across all scales — from display-sized hero headlines down to overline labels. SF Mono is reserved for code and technical content.

- **Display:** Inter, 48px, weight 700, line-height 1.2, letter-spacing -0.03em. Use for hero headlines and promotional banners.
- **H1:** Inter, 32px, weight 700, line-height 1.2, letter-spacing -0.02em. Use for page and section titles.
- **H2:** Inter, 24px, weight 700, line-height 1.2, letter-spacing -0.01em. Use for subsection headings and product category titles.
- **H3:** Inter, 20px, weight 600, line-height 1.2, letter-spacing -0.01em. Use for card titles and feature headings.
- **H4:** Inter, 18px, weight 600, line-height 1.5. Use for supporting headings and list group titles.
- **Body Large:** Inter, 18px, weight 400, line-height 1.7. Use for lead paragraphs and featured descriptions.
- **Body:** Inter, 16px, weight 400, line-height 1.5. Default body copy for paragraphs and product descriptions.
- **Body Small:** Inter, 14px, weight 400, line-height 1.5. Use for secondary content, table cells, and compact UI.
- **Caption:** Inter, 12px, weight 500, line-height 1.5, letter-spacing 0.01em. Use for supporting metadata, timestamps, and fine print.
- **Overline:** Inter, 11px, weight 600, line-height 1.5, letter-spacing 0.08em, uppercase. Use for section labels, category tags, and promotional badges.

- **Font stacks:**
  - Sans-serif (primary): `Inter, SF Pro Display, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica, Arial, sans-serif`
  - Monospace (code): `SF Mono, Fira Code, Cascadia Code, monospace`

- **Font weights:** 400 (Regular), 500 (Medium), 600 (Semibold), 700 (Bold)

## Layout

Layout follows a grid composition anchored to an 8px spatial grid. All spacing values are multiples or subdivisions of 8px, ensuring consistent vertical rhythm and horizontal alignment across cards, sections, and component internals.

- **Layout type:** Grid
- **Content width:** Full Bleed hero sections; contained content areas at max-width
- **Base unit:** 8px (with 4px half-step for tight adjustments)
- **Scale:** 4px, 8px, 12px, 16px, 24px, 32px, 40px, 48px, 56px, 64px
- **Section padding:** 48px (standard), 64px (generous)
- **Card padding:** 24px
- **Gaps:** 16px (default grid gap)

Preserve the grid-based structural frame before changing ornament or component styling. Use 8px as the base rhythm and let larger gaps step up from that cadence instead of introducing unrelated spacing values.

## Elevation & Depth

Depth is communicated through a five-step shadow scale, progressing from subtle (xs) to dramatic (xl). In dark mode, shadow opacity increases to maintain perceptible elevation against darker backgrounds.

- **Surface style:** Flat with shadow-driven elevation
- **Borders:** 1px solid #E0E0E2 (light) / 1px solid #3A3A3A (dark) — used on cards, inputs, and dividers

- **Shadow scale (light mode):**
  - xs: `0 1px 2px rgba(0,0,0,0.05)` — Subtle lift for inline elements
  - sm: `0 2px 4px rgba(0,0,0,0.08)` — Default card resting state
  - md: `0 4px 12px rgba(0,0,0,0.10)` — Card hover, dropdown panels
  - lg: `0 8px 24px rgba(0,0,0,0.12)` — Elevated/featured cards
  - xl: `0 16px 48px rgba(0,0,0,0.16)` — Modals, overlays, hero callouts

- **Shadow scale (dark mode):**
  - xs: `0 1px 2px rgba(0,0,0,0.20)`
  - sm: `0 2px 4px rgba(0,0,0,0.25)`
  - md: `0 4px 12px rgba(0,0,0,0.30)`
  - lg: `0 8px 24px rgba(0,0,0,0.35)`
  - xl: `0 16px 48px rgba(0,0,0,0.45)`

Surfaces should read as elevated via shadow first, with borders only reinforcing structure when needed. Keep shadow recipes consistent across hero panels, product cards, and controls so the page reads as one material system.

## Shapes

Shapes rely on a six-step radius system from tight (4px) to pill (9999px). Product cards and content surfaces use the mid-range radii (8–16px), while buttons and badges use the tighter or pill ends.

- **Corner radii:** 4px (xs), 8px (sm), 12px (md), 16px (lg), 24px (xl), 9999px (full/pill)
- **Usage guidance:**
  - Buttons: 8px (default), 4px (small), 12px (large)
  - Cards: 12px
  - Inputs: 8px
  - Tags/Badges: 9999px (pill)
  - Avatars/Icons: 9999px (circle)

Use the radius family intentionally: larger surfaces can open up, but controls and badges should stay within the same rounded DNA.

## Components

Anchor interactions to the following component definitions. All components use design tokens for consistency.

### Buttons

Four variants at three sizes, all using semibold (600) weight Inter.

- **Primary:** Background #E30612, text #FFFFFF, border-radius 8px, padding 12px 24px. Hover darkens to #B0050E with sm shadow. Use for primary CTAs: "Add to Cart", "Buy Now", "See Offer".
- **Secondary:** Background #F4F4F6, text #323232, 1px solid #E0E0E2 border, border-radius 8px, padding 12px 24px. Hover background shifts to #E0E0E2. Use for secondary actions: "Compare", "Save", "Details".
- **Ghost:** Transparent background, text #E30612, border-radius 8px, padding 12px 24px. Hover fills with #F4F4F6 surface. Use for tertiary actions: "Cancel", "Back", inline links.
- **Destructive:** Background #E30612, text #FFFFFF, border-radius 8px, padding 12px 24px. Hover reduces opacity to 0.9. Use for destructive actions: "Remove", "Delete".

- **Sizes:**
  - Small: font-size 14px, padding 8px 16px, border-radius 4px
  - Default: font-size 16px, padding 12px 24px, border-radius 8px
  - Large: font-size 18px, padding 16px 32px, border-radius 12px

- **States:** Disabled buttons render at 40% opacity with `cursor: not-allowed`.

### Cards

- **Default Card:** Background #FFFFFF, 1px solid #E0E0E2 border, border-radius 12px, padding 24px, shadow sm. On hover, shadow elevates to md. Max-width 320px. Use for product tiles, info blocks, and listing items.
- **Elevated Card:** Background #FFFFFF, no border, border-radius 12px, padding 24px, shadow lg. On hover, shadow elevates to xl. Use for featured/promoted products, sale highlights, and hero callouts.

### Inputs

- **Default Input:** Background #FFFFFF, text #323232, 1px solid #E0E0E2 border, border-radius 8px, padding 12px 16px. On focus, border turns #E30612 with a `0 0 0 3px rgba(227,6,18,0.12)` ring.
- **Error State:** Border turns #E30612, focus ring intensifies to `0 0 0 3px rgba(227,6,18,0.18)`. Error message in 12px #E30612 below the input.
- **Disabled State:** Background #F4F4F6, text #BDBDBD, `cursor: not-allowed`.
- **Labels:** 14px, weight 500, text #323232. Placed above the input with 6px gap.
- **Hints:** 12px, text #757575. Placed below the input.

## Do's and Don'ts

Use these constraints to keep all pages and generated UI aligned with the Brico Depot brand system.

### Do

- Do use #E30612 red as the sole primary accent for CTAs, price callouts, and emphasis states.
- Do keep spacing aligned to the 8px grid rhythm (4px half-step permitted for fine adjustments only).
- Do use the shadow scale consistently — sm for resting cards, md for hover, lg for featured, xl for modals.
- Do keep corner radii within the 4px–24px family; only use 9999px (pill) for badges and tags.
- Do maintain high contrast: charcoal (#323232) text on white, white text on red.
- Do use Inter at all type sizes — do not introduce additional typefaces.
- Do support both light and dark modes using the semantic color tokens.

### Don't

- Don't introduce accent colors outside the core palette (red, charcoal, grey, light grey) unless adding a new semantic state.
- Don't use shadows or blur recipes not in the five-step shadow scale.
- Don't hardcode color hex values — always reference design tokens so global updates propagate.
- Don't mix border-radius values outside the defined scale (4, 8, 12, 16, 24, 9999).
- Don't use font weights other than 400, 500, 600, 700.
- Don't override the 8px grid with arbitrary spacing values.

## Motion

Motion should feel snappy and utilitarian — reinforcing the practical, no-nonsense Brico Depot brand. Transitions are quick, easing is smooth, and animation is reserved for meaningful state changes (hover feedback, panel reveals, cart updates) rather than decorative flourish.

**Motion Level:** Moderate

**Durations:** 150ms (micro-interactions, hover), 200ms (state transitions), 300ms (panel/modal reveals)

**Easings:** `ease`, `cubic-bezier(0.4, 0, 0.2, 1)` (Material standard)

**Hover Patterns:** Background color shift (150ms), shadow elevation step (200ms), subtle scale on cards

**Transition Properties:** `background 0.15s, box-shadow 0.15s, opacity 0.15s, border-color 0.15s, transform 0.2s`
