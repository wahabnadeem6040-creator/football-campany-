---
name: Pro Pitch Velocity
colors:
  surface: '#121413'
  surface-dim: '#121413'
  surface-bright: '#383a38'
  surface-container-lowest: '#0d0f0e'
  surface-container-low: '#1a1c1b'
  surface-container: '#1e201f'
  surface-container-high: '#282a29'
  surface-container-highest: '#333534'
  on-surface: '#e2e3e0'
  on-surface-variant: '#c1c9c0'
  inverse-surface: '#e2e3e0'
  inverse-on-surface: '#2f312f'
  outline: '#8b938b'
  outline-variant: '#414942'
  surface-tint: '#a2d1b1'
  primary: '#a2d1b1'
  on-primary: '#093821'
  primary-container: '#0d3b24'
  on-primary-container: '#78a688'
  inverse-primary: '#3c674d'
  secondary: '#bfd42e'
  on-secondary: '#2d3400'
  secondary-container: '#a3b802'
  on-secondary-container: '#3d4600'
  tertiary: '#eac349'
  on-tertiary: '#3c2f00'
  tertiary-container: '#cca830'
  on-tertiary-container: '#4f3e00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bdeecc'
  primary-fixed-dim: '#a2d1b1'
  on-primary-fixed: '#002110'
  on-primary-fixed-variant: '#234f36'
  secondary-fixed: '#d8ee48'
  secondary-fixed-dim: '#bcd12b'
  on-secondary-fixed: '#191e00'
  on-secondary-fixed-variant: '#424b00'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#121413'
  on-background: '#e2e3e0'
  surface-variant: '#333534'
typography:
  display-xl:
    fontFamily: Oswald
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: 0.02em
  display-xl-mobile:
    fontFamily: Oswald
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Oswald
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: 0.03em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Oswald
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0.04em
  title-md:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 26px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter-xs: 0.25rem
  gutter-sm: 0.5rem
  gutter-md: 1rem
  gutter-lg: 1.5rem
  gutter-xl: 2.5rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  margin-desktop: 3.5rem
  section-gap: 5rem
---

## Brand & Style

This design system targets elite football athletes, collectors, and passionate players who demand tournament-grade performance gear. The visual mood captures the electric atmosphere of nocturnal stadium lights striking manicured grass—combining deep, atmospheric turf tones with luminous, technical accents.

The aesthetic leans into **High-Contrast Athletic Modernism with Glassmorphism**. It contrasts pitch blacks and deep stadium turf greens against razor-sharp white and high-voltage neon-lime strikes. The aesthetic projects authority, physical momentum, and premium precision. Surfaces utilize low-opacity frosted glass and micro-line tactical pitch geometries, balancing raw sports intensity with luxury digital retail clarity.

## Colors

The palette establishes an immersive stadium experience built for nighttime high-performance retail:

- **Primary (`#0D3B24`)**: Deep stadium pitch green. Used for immersive structural backdrops, elevated category headers, luxury badges, and focal brand moments.
- **Secondary (`#E2F952`)**: High-voltage neon-lime. Provides electric sporting contrast for prime calls-to-action, key performance statistics, flash badges, and hover focus rings.
- **Tertiary (`#D4AF37`)**: Championship metallic gold. Applied selectively for limited editions, official FIFA/championship partner badges, prestige tiers, and star ratings.
- **Neutral (`#0A0C0B`)**: Pure pitch darkness. Forms base canvas and backdrop layers, supported by `#111412` for elevated card containers and `#1A1F1C` for interactive borders.
- **White (`#FFFFFF`)**: Stark, high-definition white used for crisp display typography, crisp icon glyphs, and high-visibility data points.

## Typography

The type system pairs athletic energy with technical clarity:

- **Headlines & Display (Oswald)**: Set in uppercase to mimic jersey names, arena scoreboards, and technical product serials. Heavy condensed proportion drives forward velocity.
- **Body & Product Descriptions (Manrope)**: Delivers geometric balance, neutral legibility, and high readability across technical gear specifications.
- **Labels, Metrics & Data (Space Grotesk)**: Brings technical, precision-engineered character to boot weights, cleat configurations, prices, and sizing chips.

## Layout & Spacing

The layout model runs on an adaptable 12-column grid system built for dynamic e-commerce merchandising:

- **Desktop (1440px+)**: 12 columns with 24px gutters and 56px margins. Max content container caps at 1320px for product grids and detail views.
- **Tablet (768px - 1023px)**: 8 columns with 16px gutters and 32px safe margins.
- **Mobile (<768px)**: 4 columns with 12px gutters and 16px lateral padding. Horizontal swipe rails allow high-density browsing for boots, match balls, and apparel.

Vertical cadence relies on a strict 8px base rhythm. Product showcases use generous vertical padding (`section-gap: 5rem`) to create dramatic museum-like breathing room around hero sports gear.

## Elevation & Depth

Visual hierarchy uses luminous dark-mode layering rather than heavy drop shadows:

- **Base Level (`#0A0C0B`)**: Deep canvas simulating stadium night.
- **Level 1 (`#111412`)**: Surface containers for product cards, cart drawers, and table matrices, outlined with subtle 1px border `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Pitch Glass)**: Translucent overlays composed of `rgba(13, 59, 36, 0.45)` backed by a 16px blur (`backdrop-filter: blur(16px)`), framed with a top-lit highlight `rgba(226, 249, 82, 0.2)`.
- **Level 3 (Floating Controls)**: Navigation rails and checkout modals sit high with subtle ambient neon diffusion: `0 12px 32px -4px rgba(0, 0, 0, 0.7), 0 0 24px -2px rgba(226, 249, 82, 0.12)`.

## Shapes

The design system employs a **Soft (`1`)** shape language. Slight 4px (`0.25rem`) radials on micro-elements and 8px (`0.5rem`) on containers evoke precision-molded carbon fiber, boot stud plates, and athletic hardgoods. 

- **Cards & Containers**: 8px (`rounded-lg`) corner radius keeps silhouettes technical and industrial.
- **Interactive Badges & Chips**: 4px (`rounded`) radius maintains an aerodynamic, sharp performance look.
- **Strictly Avoid**: Bulbous pills or bubbly geometries that erode the competitive, pro-tier posture.

## Components

### Buttons
- **Primary Action (Add to Cart / Buy Now)**: High-voltage neon-lime (`#E2F952`) fill with pitch-black (`#0A0C0B`) uppercase text (`Space Grotesk`, bold). Zero box shadow resting; subtle neon glow on hover (`0 0 16px rgba(226, 249, 82, 0.4)`).
- **Secondary Action (Configure / Quick View)**: Transparent pitch-black container with 1px border (`rgba(255, 255, 255, 0.25)`), crisp white text, shifting to green-tinted surface on hover (`rgba(13, 59, 36, 0.3)`).
- **Championship Tier**: Metallic championship gold (`#D4AF37`) gradient fill with obsidian typography for collector-edition drops.

### Product Cards
- Contained within `#111412` with 1px border (`rgba(255, 255, 255, 0.06)`).
- Product imagery displays against a subtle radial gradient centered behind the gear (`rgba(13, 59, 36, 0.35)` fading into `#111412`).
- Integrated top metadata row: micro-brand tag on the left, high-contrast match ball/boot spec pill on the right.
- Price displayed in `Space Grotesk` alongside a quick-action size drawer trigger.

### Badges & Chips
- **Match Ready / Pro Edition**: Ultra-condensed badge with neon-lime indicator dot, uppercase label font, and deep green backdrop (`rgba(13, 59, 36, 0.7)`).
- **Limited Release**: Championship gold border (`1px solid #D4AF37`) with gold metallic text.
- **Size Selector Chips**: Square-proportioned 40x40mm tactile boxes with 4px radii. Inactive: `#161B18` surface with grey text. Selected: Solid white text, pitch-green background, and neon-lime active border outline.

### Input Fields & Search
- Low-profile dark slate field (`#111412`) with inset padding (12px 16px).
- Inactive state: 1px border `rgba(255, 255, 255, 0.12)`.
- Active focus state: 1px border `#E2F952` with subtle exterior glow `rgba(226, 249, 82, 0.15)`. Floating placeholder transitions into `label-caps` in uppercase.

### Checkboxes & Radios
- Sharp 2px rounded square checkboxes with pitch dark core.
- Checked state fills with `#E2F952`, bearing an obsidian-black angular check icon.