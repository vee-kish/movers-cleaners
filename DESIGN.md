---
name: Trust & Energy
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#62fae3'
  on-secondary-container: '#007165'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001e2c'
  on-tertiary-container: '#008ebf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#62fae3'
  secondary-fixed-dim: '#3cddc7'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built on the pillars of **Authority, Freshness, and Reliability**. It targets homeowners and businesses seeking premium cleaning and moving services where trust is the primary currency. The aesthetic is "Corporate Modern"—a balance of rigorous professional structure and a welcoming, high-energy atmosphere.

The visual narrative utilizes heavy whitespace to evoke a sense of "cleanliness" and organization. High-quality photography featuring professional staff in action and sparkling interiors is central to the experience, humanizing the brand while reinforcing the quality of service. The interaction model is smooth and predictable, providing users with a frictionless path from service discovery to booking.

## Colors

The palette is strategically split between stability and vitality. 

- **Deep Navy (#0A192F):** Used for headers, primary buttons, and foundational elements to establish authority and trust.
- **Vibrant Teal (#2DD4BF):** Acts as the "freshness" accent. It is used for primary calls-to-action, success states, and highlighting key service benefits.
- **Off-White (#F8FAFC):** The primary background color, providing a crisp, gallery-like canvas that makes photography and typography stand out.
- **Neutral Grays:** Used for secondary text and borders to maintain a sophisticated hierarchy without cluttering the visual field.

## Typography

This design system employs a dual-font strategy to maximize both impact and legibility. 

**Montserrat** is used for headings. Its geometric, bold nature conveys confidence and a modern edge. For displays and large headlines, use a tighter letter-spacing to create a "locked-in" professional look.

**Inter** is used for all body text and UI labels. Chosen for its exceptional readability at small sizes and its neutral, systematic feel, it ensures that logistical information (like pricing and service details) is consumed effortlessly.

## Layout & Spacing

The system follows a **fixed-grid approach** for desktop to maintain a controlled, premium editorial feel, while transitioning to a fluid layout for mobile devices.

- **Desktop:** 12-column grid with a 1280px max-width, 24px gutters, and 48px side margins.
- **Tablet:** 8-column grid with 24px margins.
- **Mobile:** 4-column grid with 16px margins.

Spacing follows an 8px scale. Use `lg` (48px) and `xl` (80px) vertical spacing between major sections to emphasize the "clean" brand persona. Content density should remain low to prevent overwhelming the user during stressful tasks like moving.

## Elevation & Depth

Depth is handled through a combination of **tonal layering** and **ambient shadows**. 

- **Level 0 (Flat):** Used for the main background (#F8FAFC).
- **Level 1 (Card):** White surfaces (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(10, 25, 47, 0.05)). This is the primary container for service cards and pricing tables.
- **Level 2 (Interactive):** Used for hover states on cards and buttons. Shadows become slightly more pronounced (0px 10px 30px rgba(10, 25, 47, 0.10)) to provide tactile feedback.

Avoid heavy borders; use subtle 1px strokes in a light gray (#E2E8F0) only when necessary to define boundaries between similar white elements.

## Shapes

The design system utilizes **Rounded (0.5rem / 8px)** corners as the standard. This choice softens the "corporate" navy blue, making the brand feel approachable and friendly without losing its professional edge.

- **Buttons & Inputs:** 8px radius.
- **Service Cards:** 16px (rounded-lg) to create a soft, container-like feel for photography.
- **Checkboxes:** 4px radius for a crisp but non-aggressive look.
- **Icon Containers:** Circular (full-rounded) when used as decorative accents for service features.

## Components

### Buttons
- **Primary:** Deep Navy background with White text. On hover, background shifts to a slightly lighter tint or adds a Teal bottom border.
- **Action (CTA):** Vibrant Teal background with Navy text. This is reserved for "Book Now" or "Get a Quote."
- **Ghost:** Transparent background with a Navy stroke. Used for secondary actions like "View Gallery."

### Service Cards
Feature a high-quality image with a 16px top-radius. The content area below uses plenty of padding (24px) with a bold Montserrat sub-heading and a concise Inter body description. A subtle hover transition should lift the card and deepen the shadow.

### Pricing Tables
Transparent headers with Navy text. Rows alternate with a very faint tint of Off-White. Key "Recommended" tiers are highlighted with a Teal border and a "Most Popular" chip at the top.

### Input Fields
Large, accessible touch targets (min-height 48px). Use a 1px gray border that transitions to Teal on focus. Error states use a soft red stroke and a small descriptive label below the field.

### Progress Indicators
For multi-step moving quotes, use a horizontal stepper with Teal icons to maintain momentum and energy throughout the data-entry process.