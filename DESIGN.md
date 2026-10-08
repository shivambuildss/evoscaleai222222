---
name: Obsidian Kinetic
colors:
  surface: '#121318'
  surface-dim: '#121318'
  surface-bright: '#38393f'
  surface-container-lowest: '#0d0e13'
  surface-container-low: '#1a1b21'
  surface-container: '#1e1f25'
  surface-container-high: '#292a2f'
  surface-container-highest: '#34343a'
  on-surface: '#e3e1e9'
  on-surface-variant: '#bdc8d1'
  inverse-surface: '#e3e1e9'
  inverse-on-surface: '#2f3036'
  outline: '#87929a'
  outline-variant: '#3e484f'
  surface-tint: '#7bd0ff'
  primary: '#8ed5ff'
  on-primary: '#00354a'
  primary-container: '#38bdf8'
  on-primary-container: '#004965'
  inverse-primary: '#00668a'
  secondary: '#c0c1ff'
  on-secondary: '#1000a9'
  secondary-container: '#3131c0'
  on-secondary-container: '#b0b2ff'
  tertiary: '#bccbff'
  on-tertiary: '#002a78'
  tertiary-container: '#94aeff'
  on-tertiary-container: '#003ba1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#c4e7ff'
  primary-fixed-dim: '#7bd0ff'
  on-primary-fixed: '#001e2c'
  on-primary-fixed-variant: '#004c69'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#121318'
  on-background: '#e3e1e9'
  surface-variant: '#34343a'
typography:
  display-hero:
    fontFamily: Geist
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Geist
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-lg:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-mono:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-lg: 2rem
  margin: 1.25rem
  margin-md: 2.5rem
  margin-lg: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system embodies the intersection of elite enterprise advisory and advanced machine intelligence. The aesthetic rejects stereotypical sci-fi tropes, glowing neon matrices, and overt robot motifs. Instead, it projects the authority, quiet confidence, and calculated precision of a top-tier institutional strategy firm orchestrating mission-critical transformation.

### Visual Aesthetic & Philosophy
- **Style:** Precision Minimalist Glassmorphism layered over structured obsidian geometry.
- **Tone & Mood:** Authoritative, mathematical, luminous, discrete, and technically flawless.
- **Emotional Response:** Inspires absolute confidence in enterprise scale, technological superiority, and institutional discretion.

### Key Visual Tenets
- **Obsidian Substrates:** Surface hierarchy relies on stepped deep-space dark tones rather than pure pitch black, creating rich physical dimension.
- **Atmospheric Luminance:** Color is treated as controlled light emission—subtle gradient hems, restrained ambient backdrops, and fine illuminated borders that indicate state and priority.
- **Restraint Over Spectacle:** Animations are snappy, structural, and mechanical (150ms–250ms ease-out). No frivolous particles or decorative sci-fi HUD graphics.

## Colors

The palette establishes an ultra-refined, high-contrast dark visual hierarchy. Depth is constructed using four tonal obsidian baselines punctuated by laser-accurate cyan-blue and violet-indigo chromatic accents.

### Palette Architecture

- **Canvas & Backgrounds:**
  - `bg-base` (`#090A0F`): Deep obsidian base layer for body canvas and full-screen backgrounds.
  - `surface-1` (`#0E1017`): Low-tier elevated surfaces, card structures, and primary containers.
  - `surface-2` (`#131722`): Elevated popovers, active interaction states, dialogs, and navigation bars.
  - `surface-glass`: `rgba(14, 16, 23, 0.72)` combined with 16px hardware-accelerated blur.

- **Chromatic Luminance:**
  - `primary` (`#38BDF8`): Electric Cyan used for key focus indicators, high-leverage interactive accents, and precision metrics.
  - `secondary` (`#6366F1`): Deep Indigo utilized for visual anchors, structural secondary tags, and complex capability indicators.
  - `accent-glow` (`#2563EB` to `#818CF8`): Linear gradient applied to interactive primary CTA backgrounds, linear micro-borders, and high-impact headlines.

- **Typography & Neutrals:**
  - `text-primary` (`#F8FAFC`): Crisp, high-contrast white for headers and primary CTAs.
  - `text-secondary` (`#CBD5E1`): Soft silver for subtitles, key metrics, and leading paragraphs.
  - `text-muted` (`#94A3B8`): Muted slate for standard body copy, field hints, and captions.
  - `border-subtle` (`rgba(148, 163, 184, 0.08)`): Base layout division rules.
  - `border-glass` (`rgba(148, 163, 184, 0.16)`): Standard card and modal contours.
  - `border-active` (`rgba(56, 189, 248, 0.40)`): Elevated interactive hover outlines.

## Typography

The typographic system utilizes **Geist** for display headings, metrics, and micro-labels to convey contemporary structural precision, and **Inter** for dense, readable body passages.

### Typographic Rules
- **Display Scale Treatment:** Headlines utilize optical negative tracking (tightening down to `-0.03em`) to mimic high-end architectural layout standards.
- **Editorial Contrast:** Hero titles leverage split-weight treatments: primary keywords are rendered in full `#F8FAFC`, while supporting introductory phrases or technical subclauses use horizontal gradients fading toward `#94A3B8`.
- **Labels & Micro-Indicators:** `label-mono` is strictly uppercase with `0.08em` letter tracking, designated for status tags, system metrics, and technical capability indices.

## Layout & Spacing

The layout is built on an expansive 12-column dynamic grid configured within a strict maximum container width of `1280px` (or `1440px` for dense executive analytics dashboards). Generous vertical whitespace ensures individual advisory pillars and architectural flowcharts command immediate executive focus.

### Breakpoints & Adaptive Logic
- **Mobile (< 768px):** 4-column layout; gutter `1rem`; horizontal canvas margin `1.25rem` (`margin`). Stack cards vertically; disable split-column flows.
- **Tablet (768px – 1024px):** 8-column layout; gutter `1.5rem` (`gutter`); canvas margin `2.5rem` (`margin-md`).
- **Desktop (> 1024px):** 12-column layout; gutter `2rem` (`gutter-lg`); canvas margin `5rem` (`margin-lg`). Two- and three-tier card structures activate side-by-side configurations.

### Vertical Rhythm
Section blocks consistently apply `space-3xl` (`6rem`) margins on desktop and `space-2xl` (`4rem`) on mobile devices, preventing informational clutter and maintaining a disciplined presentation.

## Elevation & Depth

Depth in this system avoids heavy, muddy drop shadows. Instead, it relies on disciplined surface luminescence, translucent glass refraction, and precision backlights.

### Surface Elevation Levels

1. **Level 0 (Base Canvas):**
   - Flat `#090A0F`. Non-elevated, light-absorbent plane.

2. **Level 1 (Cards & Structural Modules):**
   - Background: `rgba(14, 16, 23, 0.70)`.
   - Backdrop Filter: `blur(16px)`.
   - Border: `1px solid rgba(148, 163, 184, 0.08)`.
   - Shadow: `0 4px 20px -2px rgba(0, 0, 0, 0.45)`.

3. **Level 2 (Hovered Cards & Flyouts):**
   - Background: `rgba(19, 23, 34, 0.85)`.
   - Backdrop Filter: `blur(20px)`.
   - Border: `1px solid rgba(56, 189, 248, 0.28)`.
   - Shadow: `0 12px 32px -4px rgba(0, 0, 0, 0.65), 0 0 24px -6px rgba(56, 189, 248, 0.12)`.

4. **Level 3 (Modals, Overlays, Command Bars):**
   - Background: `rgba(14, 16, 23, 0.94)`.
   - Backdrop Filter: `blur(24px)`.
   - Border: `1px solid rgba(99, 102, 241, 0.35)`.
   - Shadow: `0 24px 48px -8px rgba(0, 0, 0, 0.80), 0 0 32px -4px rgba(99, 102, 241, 0.15)`.

### Gradient Radial Backdrops
For high-impact visual zones (such as case studies and architecture diagrams), position an underlaid elliptical gradient: `radial-gradient(ellipse 60% 40% at 50% 0%, rgba(56, 189, 248, 0.08) 0%, rgba(99, 102, 241, 0.04) 45%, transparent 75%)`.

## Shapes

The geometric framework balances technical rigor with modern refinement. Angles avoid playful bubbly curves, maintaining a crisp, architectural profile across every element.

### Corner Radius System
- **Base Components (`rounded-sm` / 0.25rem):** Micro badges, metric pills, input fields, and inline code tags.
- **Mid-Tier Elements (`rounded-md` / 0.5rem):** Action buttons, control elements, drop-downs, and popover menus.
- **Structural Containers (`rounded-lg` / 0.75rem):** System cards, enterprise showcase grids, and modal frames.
- **Full Radius (`rounded-full`):** Reserved exclusively for circular icon housings, presence status indicators, and avatar cutouts.

## Components

### Buttons
- **Primary CTA:**
  - Gradient surface: `linear-gradient(135deg, #38BDF8 0%, #2563EB 50%, #6366F1 100%)`.
  - Text: `#FFFFFF`, `label-lg`, weight 500.
  - Border: None, with an inset highlight: `box-shadow: inset 0 1px 1px rgba(255, 255, 255, 0.3)`.
  - State: On hover, slight ambient radiance (`box-shadow: 0 0 20px rgba(56, 189, 248, 0.4)`), smooth scale transform `1.01`.
- **Secondary (Glass Outline):**
  - Surface: `rgba(14, 16, 23, 0.6)`.
  - Border: `1px solid rgba(148, 163, 184, 0.16)`.
  - Text: `#CBD5E1`.
  - State: On hover, border transitions to `rgba(148, 163, 184, 0.35)` with text shifting to `#F8FAFC`.

### Cards & Content Modules
- **Structure:** `surface-1` background, 16px padding on mobile, 24px–32px on desktop.
- **Top Accent Line:** Subtle inset line with `linear-gradient(90deg, transparent, rgba(56, 189, 248, 0.3), transparent)` visible along the top 1px border.
- **Hover Behavior:** Translates `-2px` on the Y-axis over 200ms; border transitions smoothly from `border-glass` to `border-active`.

### Micro-Badges & Status Chips
- **Design:** Compact height (24px), horizontal padding (8px), shape `rounded-sm`.
- **Color Variant (Live / Operational):**
  - Surface: `rgba(56, 189, 248, 0.08)`.
  - Text: `#38BDF8`, `label-mono`.
  - Leading Indicator: 6px pulsing dot (`#38BDF8`).
- **Color Variant (Enterprise Capability):**
  - Surface: `rgba(99, 102, 241, 0.10)`.
  - Border: `1px solid rgba(99, 102, 241, 0.20)`.
  - Text: `#818CF8`, `label-mono`.

### Form Fields & Inputs
- **Base Style:** Background `rgba(14, 16, 23, 0.8)`, height 44px, shape `rounded-md`.
- **Border:** `1px solid rgba(148, 163, 184, 0.14)`.
- **Text:** Input text `#F8FAFC`, placeholder `#94A3B8`.
- **Focus State:** Border shifts cleanly to `#38BDF8`; subtle glow outline `0 0 0 1px #38BDF8`.

### Checkboxes & Radios
- **Unchecked:** Flat `rgba(14, 16, 23, 0.8)`, `1px solid rgba(148, 163, 184, 0.25)`.
- **Checked:** Background `#2563EB`, inner check mark `#FFFFFF`, accent border `#38BDF8`.

### Specialized Agency Component: Metric / ROI Showcase Block
- **Layout:** High-contrast statistical counter card.
- **Primary Value:** `display-hero` sized typographic counter featuring an electric-cyan-to-white vertical gradient.
- **Labeling:** Structured `label-mono` subtext detailing client KPI transformation and data integrity verification metrics.