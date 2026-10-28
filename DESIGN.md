---
name: Taller AB Workshop System
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#343944'
  surface-container-lowest: '#090e17'
  surface-container-low: '#171c25'
  surface-container: '#1b2029'
  surface-container-high: '#252a34'
  surface-container-highest: '#30353f'
  on-surface: '#dee2f0'
  on-surface-variant: '#c2c6d8'
  inverse-surface: '#dee2f0'
  inverse-on-surface: '#2c303b'
  outline: '#8c90a1'
  outline-variant: '#424656'
  surface-tint: '#b3c5ff'
  primary: '#b3c5ff'
  on-primary: '#002b75'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#0054d6'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#b7c4ff'
  on-tertiary: '#002682'
  tertiary-container: '#3d66ef'
  on-tertiary-container: '#f9f7ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b7c4ff'
  on-tertiary-fixed: '#001551'
  on-tertiary-fixed-variant: '#0039b5'
  background: '#0f131d'
  on-background: '#dee2f0'
  surface-variant: '#30353f'
typography:
  headline-xl:
    fontFamily: Barlow Condensed
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 60px
    letterSpacing: 0.02em
  headline-xl-mobile:
    fontFamily: Barlow Condensed
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: 0.01em
  headline-lg-mobile:
    fontFamily: Barlow Condensed
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 30px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
  price-display:
    fontFamily: Barlow Condensed
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system translates the high-performance cycling workshop environment into a digital interface. Built for performance cyclists, mountain bikers, and commuters in the Atacama region (Copiapó & Tierra Amarilla), the aesthetic delivers professional technical precision paired with high-voltage motorsport energy.

The aesthetic fuses **Modern Technical Motorsport** with **Neon Cyber-Workshop UI**:
- **Atmospheric Depth:** Deep midnight tones evoke cleanroom mechanical workshops, dark toolboards, and matte carbon frames.
- **Electric Precision:** High-contrast racing cobalt and electric cyan neon lines direct visual focus, signifying diagnostic certainty, calibration, and workshop reliability.
- **Utilitarian Speed:** Condensed, athletic display typography conveys power and agility, balanced with surgical body text optimized for dense pricing tables, part lists, and service specs.

## Colors

The palette establishes an aggressive dark theme optimized for technical clarity and glowing neon contrasts.

### Core Roles
- **Primary (`#0066FF`):** Racing Blue. Used for core interactive items, prominent badges, branding insignias, and selected states.
- **Secondary (`#00F0FF`):** Electric Cyan Neon. Serves as the primary high-voltage focal highlight, luminescent borders, active glow indicators, and metric data.
- **Tertiary (`#1D4ED8`):** Deep Cobalt. Applied to container outlines, sub-headers, secondary badges, and gradient blends.
- **Neutral Base (`#0A0F18` / `#05080E`):** Midnight Obsidian. Darkened workshop background surfaces providing infinite contrast for neon layers.

### Functional States & Layers
- **Surface Elevation 1 (`#0D1524`):** Card panels and list modules.
- **Surface Elevation 2 (`#142036`):** Hover tiers, interactive slots, active rows.
- **Text Primary (`#FFFFFF`):** High-readability crisp white for titles and critical prices.
- **Text Muted (`#94A3B8`):** Slate for specifications, disclaimer notes, and technical metadata.

## Typography

The type system implements a deliberate duality:

1. **Barlow Condensed** conveys industrial velocity. Rendered with uppercase styling for service names, price banners, callouts, and promotions, it mirrors performance suspension tuning and bike shop tooling signage.
2. **Inter** provides neutral, sterile engineering readability for mechanical specifications, currency details, disclaimers, and data metrics.

### Letter-Spacing Rules
Display titles use slight tracking expansion (`0.01em` to `0.02em`) to ensure legibility when set in heavy uppercase. Labels and micro-badges use expanded tracking (`0.05em` to `0.08em`) to mimic stamped serial badges on bicycle frames.

## Layout & Spacing

The layout is constructed on an 8pt technical modular system, translating physical workshop tool racks and instrument displays into responsive web components.

### Grid Rules
- **Desktop (1024px+):** 12-column layout with `2rem` outer margin and `1.25rem` gutters. Service packages utilize a 2-column or 3-column split with high horizontal contrast.
- **Tablet (768px - 1023px):** 8-column layout with `1.5rem` margins.
- **Mobile (< 768px):** 4-column compact layout with `1rem` margin and `0.75rem` gutters. Service rows stack linearly into vertical telemetry ribbons.

### Density & Rhythms
Workshop pricing cards enforce tight vertical padding (`space-md`) paired with generous lateral space (`space-lg`) to preserve the feeling of diagnostic dashboards.

## Elevation & Depth

Visual hierarchy does not rely on traditional muddy drop shadows; instead, it utilizes **Luminescent Containment** and **Backlit Workshop Tiers**:

- **Tier 0 (Canvas):** Pure `#05080E` base with optional subtle radial gradients emitting from the top center using `radial-gradient(ellipse at top, #0066FF18 0%, transparent 70%)`.
- **Tier 1 (Surface Cards):** `#0D1524` with a 1px border colored `#0066FF40`.
- **Tier 2 (Active / Featured Items):** Backlit highlights utilizing `#0066FF` or `#00F0FF` inner border rings complemented by an exterior cyan halo: `box-shadow: 0 0 16px -2px rgba(0, 240, 255, 0.45)`.
- **Tier 3 (Floating Overlays / Modals):** `#142036` layered with `backdrop-filter: blur(12px)` and double border rings (1px outer cyan at 40%, 1px inner midnight glow).

## Shapes

With a roundedness factor of `2`, the system strikes a balance between aerodynamic engineering and rugged durability:

- **Base Radius (`0.5rem` / `8px`):** Applied to service cards, action buttons, inputs, and interactive list tiles.
- **Badge & Pill Radius (`rounded-full` / `9999px`):** Reserved for technical status badges, verified tags, and floating communication buttons (e.g., WhatsApp and Instagram contact anchors).
- **Tooling Chamfers & Accents:** Decorative divider lines and progress indicators end with strict 90° or rounded terminal caps that match bicycle shock absorber hardware.

## Components

### Buttons
- **Primary Neon CTA:** Background gradient from `#0066FF` to `#0052CC`, pure white Barlow Condensed uppercase text, 1px top highlight `#00F0FF`, and an outer glow `0 0 14px rgba(0, 102, 255, 0.6)`. Hover elevates glow with a shift towards `#00F0FF`.
- **Ghost Workshop Button:** Transparent background, 1.5px border of `#0066FF`, crisp white text with transition to `#00F0FF` text and cyan border halo on hover.
- **WhatsApp Direct Action:** Dedicated brand container (`#25D366` accent on midnight base) accompanied by rounded-full shape and mechanical phone/chat iconography.

### Cards & Service Ribbons
- **Standard Service Item:** Full-width horizontal strip on mobile, 2-to-3 column grid on desktop. Midnight surface (`#0D1524`) framed by a 1px `#1D4ED8` border. Left-aligned technical icon in a neon circular badge; title in white Barlow Condensed; vertical divider in `#0066FF44`; right-aligned price display in electric cyan or bright white.
- **Featured / "Full" Tier Card:** Highlighted with an active linear gradient stroke `#0066FF` to `#00F0FF`, background tint with 5% primary color bleed, and an ambient outer cyan bloom.

### Badges & Category Tags
- **Workshop Stamp Badges:** Pill-shaped tags (`px-3 py-1`) with high-contrast text (`label-md`). Translucent fill (`#0066FF22`) with solid 1px cyan-blue border. Used for service turnaround times, region tags ("Copiapó", "Tierra Amarilla"), and warranty seals.

### Input Fields & Controls
- **Form Controls:** Dark recessed background (`#070B12`), border 1.5px `#1E293B`. On focus, border transitions instantly to `#00F0FF` with a cyan focus ring (`0 0 8px rgba(0, 240, 255, 0.3)`).
- **Checkboxes & Radios:** Precision squares with `0.25rem` corners. Unchecked states carry a subtle blue border. Checked state fills with `#0066FF` and renders a razor-sharp `#00F0FF` check glyph.

### Specialized Components
- **Diagnostic Price Tier:** Distinct split component placing service names and prices in high-contrast athletic typography, mimicking workshop chalkboards and race timing boards.
- **Social Action Pills:** Floating social link bars with rounded-full shapes, neon borders, and paired brand logos (`@_tallerAb`).