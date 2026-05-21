---
name: Audit & Truth System
colors:
  surface: '#101415'
  surface-dim: '#101415'
  surface-bright: '#363a3b'
  surface-container-lowest: '#0b0f10'
  surface-container-low: '#191c1e'
  surface-container: '#1d2022'
  surface-container-high: '#272a2c'
  surface-container-highest: '#323537'
  on-surface: '#e0e3e5'
  on-surface-variant: '#e8bcb6'
  inverse-surface: '#e0e3e5'
  inverse-on-surface: '#2d3133'
  outline: '#ae8782'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4aa'
  primary: '#ffb4aa'
  on-primary: '#690003'
  primary-container: '#e61919'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0000b'
  secondary: '#bec6e0'
  on-secondary: '#283044'
  secondary-container: '#3f465c'
  on-secondary-container: '#adb4ce'
  tertiary: '#bcc7de'
  on-tertiary: '#263143'
  tertiary-container: '#6a758a'
  on-tertiary-container: '#fefcff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4aa'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930006'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d8e3fb'
  tertiary-fixed-dim: '#bcc7de'
  on-tertiary-fixed: '#111c2d'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#101415'
  on-background: '#e0e3e5'
  surface-variant: '#323537'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Merriweather
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Merriweather
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  audit-stat:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '800'
    lineHeight: '1.0'
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The design system is engineered for a digital newspaper that prioritizes investigative depth, fiscal oversight, and uncompromising transparency. The brand personality is **authoritative, forensic, and bold**. It operates on the principle that "facts kill narratives," requiring a UI that feels like a high-security dossier or an official audit report.

The aesthetic follows a **High-Contrast / Modern** style with **Brutalist** undertones. It utilizes a deep, nocturnal palette to establish a serious tone, punctuated by a surgical use of vibrant red to highlight urgent data and calls to action. Visual elements should feel structural and intentional, avoiding unnecessary decoration in favor of clarity and impact.

Key visual pillars include:
- **Forensic Clarity:** High contrast between backgrounds and typography to ensure readability of dense information.
- **Structural Integrity:** Heavy use of vertical and horizontal dividers to organize complex datasets.
- **Urgency:** Red accents serve as a "warning" or "alert" system, drawing the eye to critical investigations or breaking news.

## Colors

The palette is rooted in a "Dark Mode First" philosophy to evoke the feeling of a late-night investigation or a secure terminal.

- **Primary (Urgent Red):** Used exclusively for high-impact elements like breaking news tags, primary action buttons, and critical data points.
- **Secondary (Obsidian Blue):** The primary background color. A very deep, desaturated blue that provides better depth than pure black while maintaining a serious tone.
- **Tertiary (Steel Gray):** Used for card surfaces, input fields, and secondary containers to create subtle hierarchy within the dark interface.
- **Neutral (Paper White):** High-legibility white for primary body text and headlines, ensuring maximum contrast against the dark background.
- **Accents:** Occasional use of muted gold or blue-grays for specific categories like "Fiscal Monitor" to distinguish content types without breaking the monochromatic severity.

## Typography

This design system uses a dual-font strategy to balance impact with long-form readability.

- **Headlines (Montserrat):** A robust, geometric sans-serif used for impact. Large headlines should be set with tight letter spacing to feel dense and "heavy."
- **Body (Merriweather):** A highly legible serif font specifically chosen for journalistic long-form reading. It provides the "institutional" feel of a traditional newspaper.
- **Technical/Labels (JetBrains Mono):** A monospaced font used for "meta-data" such as timestamps, source citations, and fiscal data. This reinforces the "auditor" aesthetic.

Text should never be pure gray on dark; always keep the contrast ratio high (AAA standard) to ensure accessibility for information-heavy pages.

## Layout & Spacing

The design system uses a **Fixed Grid** approach for desktop to maintain the organized structure of a formal report, transitioning to a fluid single-column for mobile.

- **Grid:** A 12-column grid system. News headlines may span 8 columns, while "Sidebars" or "Fiscal Alerts" occupy the remaining 4.
- **Spacing Rhythm:** Based on a 4px baseline. Components use consistent padding (e.g., 16px, 24px, 32px) to ensure a disciplined, geometric feel.
- **Gutters:** Generous 24px gutters are used to prevent information density from becoming overwhelming.
- **Article Layout:** Long-form content is centered with wide margins to create a focused reading experience, limiting the line length to 700px for optimal readability.

## Elevation & Depth

To maintain a "flat/modern" investigative aesthetic, depth is created through **Tonal Layers** rather than shadows.

- **Base Layer:** Deepest blue (#0F172A).
- **Surface Layer:** One step lighter (#1E293B) for cards, news snippets, and modular sections.
- **Dividers:** 1px solid lines using high-contrast white (at 10-20% opacity) or primary red for specific "urgent" section breaks.
- **Zero Shadows:** Shadows are avoided to prevent a "soft" appearance. Hierarchy is instead established through clear borders and distinct background tonal changes.
- **Backdrop Blur:** Used sparingly on navigation bars (12px blur) to maintain context while scrolling through dense articles.

## Shapes

The design system utilizes **Sharp (0px)** corners for all primary UI elements.

This choice is intentional to evoke a sense of precision, rigidity, and architectural strength. Buttons, input fields, image containers, and cards all feature 90-degree angles. This "no-nonsense" approach differentiates the product from friendlier, rounded consumer apps and aligns it with professional auditing and legal software.

## Components

### Buttons
- **Primary:** Solid Red background, white Montserrat Bold text (All Caps). 0px border radius.
- **Secondary:** Transparent background, 2px white border, white text.
- **Tertiary:** Text-only with a red underline that expands on hover.

### Cards
- **News Cards:** Tonal background (#1E293B) with a sharp 1px border. Headlines are always white.
- **Breaking News Card:** Heavy red left-border (4px) to signal urgency.

### Input Fields
- Dark backgrounds with white text and a 1px white border. On focus, the border turns Primary Red.
- Labels use the monospaced "Label-Caps" typography style to feel like a form or official document.

### Data Chips / Tags
- Small, sharp rectangles. Red background for "Breaking," Black with white border for "Investigation," and Deep Blue for "Archive."

### Lists & Navigation
- **Top Nav:** Minimalist, using Monospaced font for a "system" feel. Active states are indicated by a 2px red bottom border.
- **Article Lists:** Divided by thin 1px horizontal lines, maximizing white space between the headline and the metadata.

### The "Auditor" Tooltip
- Specialized component for citing sources. It uses a monospaced font and a high-contrast black/white style to show raw data or document links.