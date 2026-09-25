---
name: Warm Nostalgia Storybook
colors:
  surface: '#fef9f0'
  surface-dim: '#ded9d1'
  surface-bright: '#fef9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e7e2d9'
  on-surface: '#1d1c16'
  on-surface-variant: '#434843'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e7'
  outline: '#737873'
  outline-variant: '#c3c8c2'
  surface-tint: '#4f6356'
  primary: '#172a1f'
  on-primary: '#ffffff'
  primary-container: '#2d4034'
  on-primary-container: '#96ab9c'
  inverse-primary: '#b6ccbb'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#002a39'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b4050'
  on-tertiary-container: '#88abbe'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e8d7'
  primary-fixed-dim: '#b6ccbb'
  on-primary-fixed: '#0d1f15'
  on-primary-fixed-variant: '#384b3f'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#c3e8fc'
  tertiary-fixed-dim: '#a8cce0'
  on-tertiary-fixed: '#001f2b'
  on-tertiary-fixed-variant: '#274b5c'
  background: '#fef9f0'
  on-background: '#1d1c16'
  surface-variant: '#e7e2d9'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 3.75rem
    fontWeight: '600'
    lineHeight: 4.25rem
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: 3rem
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: 2rem
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '500'
    lineHeight: 1.75rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system channels the warmth, pastoral stillness, and tactile craftsmanship of hand-painted pastoral cinema. It balances nostalgic storybook romance with an editorial portfolio framework, avoiding kitsch through rigorous typographic hierarchy, restrained ornamentation, and deliberate negative space.

### Brand Personality & Mood
- **Nostalgic & Pastoral:** Reminiscent of sunlit meadows, pressed botanicals, and studio sketchbooks.
- **Crafted & Painterly:** Surfaces feel physical, evoking fine hot-press paper, deep archival inks, and gilded book-cloth.
- **Calm & Contemplative:** Unrushed pacing, generous margins, and organic transitions that encourage measured perusal over rapid consumption.

### Design Movement & Aesthetic
- **Tactile Editorial / Illustrated Naturalism:** A synthesis of classical literary publishing, traditional watercolor margins, and restrained modern layout.
- **Physical Depth Metaphors:** Cards and containers evoke heavy-weight cotton rag cards and deckled book leaves. Highlights and borders use muted mineral pigments and brass foil rather than synthetic glows.

## Colors

The palette draws directly from natural pigments: forest floor greens, parchment whites, aged metallic brass, and dusk sky washes.

### Palette Architecture
- **Primary (`#2D4034`):** Forest ink. Used for critical interactive triggers, primary headings, emphasized outlines, and strong typographic anchors. An alternate deeper forest shade (`#1E2B24`) provides maximum ink contrast for micro-copy and dense text.
- **Secondary (`#D4AF37`):** Muted leaf-gold. Reserved for curated accents, achievements, gilded highlights, badge accents, and warm focal sparks.
- **Tertiary (`#5A7D8F`):** Distant dusk blue. Used for atmospheric canvas gradients, secondary tags, quiet callouts, and cool morning water-sky backgrounds.
- **Neutral Canvas (`#F4EFE6`):** Natural warm parchment. Forms the mid-layer page background.
  - Surface Pure (`#FBF8F1`): Illuminated paper, used for primary cards, modals, and raised surfaces.
  - Surface Muted (`#FAF7F0`): Clean cream base for secondary surface fills.
  - Surface Sunken (`#EAE3D5`): Pressed sand tint for recessed wells, inactive toggles, and table headers.
- **Border Pigment (`rgba(45, 64, 52, 0.12)`): Diluted ink rule for structural lines, matching the organic character of a soft pencil ruling on paper.

## Typography

The typographic stack pairs the romantic cadence of **Playfair Display** with the clean legibility of **Plus Jakarta Sans**.

### Roles & Execution
- **Headlines (Playfair Display):** Conveys the atmosphere of chapter titles and classic literature. Headlines use optical kerning and measured line heights to accommodate sweeping ascenders and descenders. Italic variants are reserved for case-study subtitles, client roles, and evocative pull quotes.
- **Body & Interface (Plus Jakarta Sans):** Grounded, warm, and highly readable. Its open counters ensure comfortable reading over textured and cream backgrounds.
- **Handwritten Accents (Secondary Layer):** Spontaneous annotations, stamp captions, and margin notes may utilize an organic script display face (such as *Caveat* or natural handwriting) strictly for brief non-structural accents, decorative date stamps, or author notes. It must never be applied to primary navigation, body copy, or operational labels.

## Layout & Spacing

The layout philosophy follows a classical editorial grid with generous margins and asymmetrical pacing to mirror an open picture-book spread.

### Grid & Composition
- **Desktop (≥1024px):** 12-column variable grid, maximum reading canvas of `1280px`. Margins expand to `4rem` to give layouts generous breathing room. Sections often break symmetry: pairing an offset 7-column media frame with a 4-column typographic description.
- **Tablet (768px - 1023px):** 8-column grid with `2.5rem` margins and `1.5rem` gutters. Stacks asymmetric split-screens into natural vertical cadences.
- **Mobile (<768px):** 4-column fluid layout with `1.25rem` margins. Complex editorial compositions reflow into vertical story scrolls with full-bleed image moments.

### Spacing Rhythm
Spacing is intentional and expansive. Vertical flow prefers `space-xl` between modular sections, creating distinct chapter breaks rather than continuous corporate dashboard density.

## Elevation & Depth

Visual hierarchy is built through **tonal layering and warm, diffuse ambient shadows** rather than high-contrast structural elevation.

### Surface Tiers
1. **Base Field (Canvas):** `#F4EFE6` matte parchment base.
2. **Layered Card (Resting):** `#FBF8F1` cotton paper surface resting over the canvas, surrounded by a 1px border of `rgba(45, 64, 52, 0.08)` and an ambient shadow: `0 4px 20px -2px rgba(42, 60, 36, 0.05)`.
3. **Elevated Card (Hover / Focused):** Moves up 2px on the Y-axis. Shadow transitions to a deeper warm hum: `0 12px 32px -4px rgba(30, 43, 36, 0.09)`.
4. **Floating Overlays & Modals:** Backed by a warm parchment glass scrim (`rgba(244, 239, 230, 0.75)` with `8px` blur), framed with a crisp inner highlight: `inset 0 1px 0 rgba(255, 255, 255, 0.8)` and a soft base boundary: `0 24px 48px -12px rgba(30, 43, 36, 0.16)`.

### Atmosphere Canvas (Hero / Header)
Hero sections and focal banners embrace painterly washes—subtle radial and linear blends transitioning from warm dusk gold (`#F4DFB8`) and soft sage green into distant horizon blues (`#5A7D8F`). These serve as background landscapes without compromising foreground text contrast.

## Shapes

The shape system employs roundedness level **2**, striking a balance between historical bookbinding geometry and the organic soft edges of hand-cut materials.

### Corner Rules
- **Base UI Elements (Buttons, Inputs, Badges):** `0.5rem` (`rounded`) radius. Provides a welcoming, comfortable hold without turning into synthetic pill capsules.
- **Cards, Frames, & Folios:** `1rem` (`rounded-lg`) radius. Mirrors the softened corners of heirloom leather notebooks and hand-trimmed card stock.
- **Modal Sheets & Hero Feature Panes:** `1.5rem` (`rounded-xl`) radius. Evokes soft framed plates within a picture-book folio.

## Components

### Buttons
- **Primary:** Deep forest green (`#2D4034`) solid fill, pure warm cream text (`#FBF8F1`), `0.5rem` radius. Subtle inner top highlight `inset 0 1px 0 rgba(255, 255, 255, 0.15)`. Hover states warm into `#1E2B24` with a gentle 1px elevation lift.
- **Secondary / Outline:** Base cream fill (`#FAF7F0`) with a 1.5px border of `#2D4034`, dark forest text. Hover introduces a warm golden wash (`rgba(212, 175, 55, 0.12)`).
- **Tertiary / Text:** Underlined with a hand-drawn feel; uses `#2D4034` with an ink-line underline offset by `4px`, accented by an arrow icon that glides smoothly right on hover.

### Chips & Tags
- Compact tags with `0.5rem` radius, colored in pale sage (`rgba(45, 64, 52, 0.06)`) or pale dusk blue (`rgba(90, 125, 143, 0.1)`), bordered with a faint matching stroke. Typography is set in `label-sm`, uppercase with subtle tracking.
- Featured or prize badges incorporate a small gilded accent border (`#D4AF37`) with ink text.

### Input Fields
- Surface set to `#FBF8F1` with an inset field tone.
- Outlines use a warm stone tint (`rgba(45, 64, 52, 0.2)`). Focused inputs transition to a crisp `#2D4034` border with a soft brass halo ring (`0 0 0 3px rgba(212, 175, 55, 0.25)`).
- Placeholder text is set in muted olive-gray (`rgba(45, 64, 52, 0.5)`).

### Cards & Project Folios
- Built with a `#FBF8F1` foundation, subtle ink border, and warm atmospheric shadows.
- Media elements inside cards feature soft internal rounding (`0.5rem`) and an organic matte grain texture overlay.
- Metadata bars feature faint horizontal separator rules (`1px solid rgba(45, 64, 52, 0.08)`) with `Playfair Display` titles and `Plus Jakarta Sans` details.

### Selection Controls (Checkboxes & Radios)
- Base boxes maintain a `0.25rem` radius for checkboxes and full circles for radios, framed in `#2D4034` outline.
- Active checked state fills with `#2D4034`, revealing an off-white calligraphic checkmark or inner pill.

### Narrative Quotation & Aside Panels
- Distinctive narrative component: a parchment box bordered on the left with a 3px brass spine (`#D4AF37`), filled with `#FAF7F0`, featuring italicized `headline-sm` prose and an optional handwritten-style attribution offset in the margin.