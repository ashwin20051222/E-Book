---
name: Warm Editorial Paper
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4a463f'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#7c766e'
  outline-variant: '#cdc5bc'
  surface-tint: '#615e5a'
  primary: '#040302'
  on-primary: '#ffffff'
  primary-container: '#1f1d1a'
  on-primary-container: '#898580'
  inverse-primary: '#cbc6c1'
  secondary: '#9e421e'
  on-secondary: '#ffffff'
  secondary-container: '#ff8c62'
  on-secondary-container: '#752402'
  tertiary: '#070301'
  on-tertiary: '#ffffff'
  tertiary-container: '#241c17'
  on-tertiary-container: '#90837b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7e1dc'
  primary-fixed-dim: '#cbc6c1'
  on-primary-fixed: '#1d1b18'
  on-primary-fixed-variant: '#494643'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59c'
  on-secondary-fixed: '#380c00'
  on-secondary-fixed-variant: '#7f2b08'
  tertiary-fixed: '#f0dfd6'
  tertiary-fixed-dim: '#d3c3bb'
  on-tertiary-fixed: '#221a15'
  on-tertiary-fixed-variant: '#4f453e'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  headline-xl:
    fontFamily: Literata
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-xl-mobile:
    fontFamily: Literata
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Literata
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.005em
  headline-lg-mobile:
    fontFamily: Literata
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Literata
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  headline-sm:
    fontFamily: Literata
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
  body-reading-lg:
    fontFamily: Literata
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0.005em
  body-reading-md:
    fontFamily: Literata
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 29px
    letterSpacing: 0.005em
  body-reading-sm:
    fontFamily: Literata
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  ui-body:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  ui-body-strong:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 22px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
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
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  margin-desktop-reading: auto
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system is crafted for reflective, prolonged immersion. It counters the hyper-stimulating, synthetic glare of modern interfaces by embodying the calm, deliberate qualities of printed literature and physical e-ink displays. The interface steps back, prioritizing text legibility, gentle visual rhythm, and natural eye comfort.

The aesthetic fuses **Editorial Minimalism** with **Tactile Paper Heuristics**:
- **Pure Solid Fills:** Gradients, dynamic glassmorphic blurs, and glossy highlights are banned. Every surface feels pressed from physical paper stock.
- **Micro-tactility:** Surfaces convey hierarchy through subtle pigment shifts, crisp 1px hair-thin paper borders, and microscopic page-edge shadows (1–2px), evoking genuine bookbindings and loose-leaf folios.
- **Intentional Restraint:** Visual noise is minimized to preserve the user's flow state. Spacing is generous, interactions are steady and non-jarring, and visual anchors rely on deliberate, classic editorial typesetting.

## Colors

The palette simulates physical ink, wood-pulp paper, and cloth-bound bindings. Primary interactions use terracotta earth pigments, while the structural canvas avoids sterile cold whites in favor of balanced warm cream tones.

### Palettes & Themes

1. **Paper (Default Canvas):**
   - Background Canvas: `#FAF8F4`
   - Surface / Page: `#FFFFFF`
   - Primary Text (Printer's Ink): `#1F1D1A` (contrast ratio 15.6:1 against Paper)
   - Secondary Text (Muted Graphite): `#6B665E` (contrast ratio 5.1:1 against Paper)
   - Hairline Borders: `#E6E1D8`
   - Terracotta Accent (Interactive/Active): `#B5532E`
   - Terracotta Container (Subtle Highlight/Selected): `#F4E3DA`

2. **Sepia (Reading Mode):**
   - Background Canvas: `#F3E7D0`
   - Surface: `#EADBC2`
   - Primary Text: `#3B2F20`
   - Secondary Text: `#726350`
   - Hairline Borders: `#DCCDB3`
   - Accent: `#9C4320`
   - Accent Container: `#E4CDBE`

3. **Dark (Nocturnal Paper):**
   - Background Canvas: `#1B1A18`
   - Surface: `#252320`
   - Primary Text: `#E8E4DC`
   - Secondary Text: `#9C968C`
   - Hairline Borders: `#383530`
   - Accent: `#D47551`
   - Accent Container: `#3A2A23`

4. **Black OLED (Pure E-Ink Contrast):**
   - Background Canvas: `#000000`
   - Surface: `#121212`
   - Primary Text: `#CFCBC2`
   - Secondary Text: `#827E77`
   - Hairline Borders: `#292826`
   - Accent: `#E2805B`
   - Accent Container: `#2C1E18`

All foreground-to-background combinations meet or exceed WCAG AA standards (minimum 4.5:1 for body copy and 3.0:1 for interface components and graphical controls).

## Typography

The type system implements a dual-font structure:
- **Literata (Serif):** Dedicated entirely to reading matter, book titles, chapter subtitles, and reflective literary quotes. Designed for digital screens, its organic serifs, angled stress, and comfortable proportions create effortless long-form reading without eye strain.
- **Inter (Geometric Humanist Sans):** Reserved for chrome UI, navigation items, reader configuration tools, metadata, pagination badges, and status labels. It establishes an unambiguous distinction between the "tool" and the "content."

### Typographic Rules
- Reader content uses a relaxed line height (`1.7x`–`1.8x`) to ensure smooth visual tracking across page lines.
- Reading body text maximum line length is constrained between 60 to 75 characters (approx. `640px`–`720px` container width) to avoid ocular fatigue.
- Material Symbols Outlined are set with a strict `1.5px` stroke weight, aligning visually with the stem weight of Inter medium labels.

## Layout & Spacing

The layout is built upon an 8-point rhythmic grid (with a 4px sub-unit for compact metadata and micro-labels).

### Layout System
- **Desktop (min-width: 1024px):** Uses an asymmetrical two-column or three-column layout. When browsing libraries, content aligns to a 12-column grid with `24px` gutters. When in **Reader View**, outer sidebars collapse or pin, and reading content snaps to a centered single- or dual-page container with max width `760px` (or `1200px` for side-by-side spread).
- **Tablet (640px – 1023px):** Adapts to an 8-column layout. Margins tighten to `24px`. Toolbars shift to edge docking.
- **Mobile (&lt; 640px):** Single-column layout with `16px` outer margins. All critical touch targets (page turning zones, bookmarking, brightness controls) cluster within the bottom ergonomic thumb zone (bottom 40% of viewport).

### Touch & Accessibility Standards
- Every interactive element preserves an explicit hit target of at least `48px × 48px`.
- Page-turning tap targets on mobile cover wide lateral bands (20% left edge = previous, 60% center = toggle UI, 20% right edge = next).

## Elevation & Depth

To sustain the physical paper metaphor, this system eschews dramatic dropshadows, blurred scrims, and layered Z-axis projections.

Depth is achieved through **Surface Pigmentation** and **Microscopic Binding Relief**:
- **Canvas Base:** `#FAF8F4` sets the grounding plane.
- **Page Layer (Elevated Surface):** `#FFFFFF` sits flush upon the canvas, delineated by a clean `1px solid #E6E1D8` hairline stroke.
- **Physical Book Covers:** The single exception to the zero-shadow rule is book covers, which carry a tactile paper-edge shadow: `box-shadow: 0 1px 2px rgba(31, 29, 26, 0.08), 0 2px 4px rgba(31, 29, 26, 0.04)`. This mimics the spine and card thickness of a paperback.
- **Sheets, Overlays, and Modals:** Reader settings drawers slide upward from bottom screen boundaries bordered by a `1px` top boundary stroke (`#E6E1D8`). Backdrop scrims use an un-blurred, warm ink wash: `rgba(31, 29, 26, 0.35)`.

## Shapes

The shape system honors the physical binding of reading mediums:

- **Book Covers & Folios:** Form-locked to a classical **2:3 aspect ratio** with a subtle `4px` corner radius, representing clean-cut book board. The left edge features a 2px pseudo-spine crease highlight.
- **Cards, Sheets & Overlays:** Standardized to a `12px` border radius (`rounded-lg`), evoking rounded deckle-edge journals.
- **Buttons, Sliders & Search Fields:** Styled with an `8px` corner radius (`rounded`), balancing structural geometry with soft tactile comfort.
- **Reading Progress & Status Pills:** Configured with full pill styling (`rounded-full` / `9999px`) for floating reading page counters and category chips.

## Components

### Buttons
- **Primary:** Solid terracotta `#B5532E` fill, `#FFFFFF` text, `8px` corner radius. Height `48px`, horizontal padding `24px`. Flat fill without gradient or shadow. Active state darkens to `#984323`.
- **Secondary / Outlined:** `#FFFFFF` or transparent fill with a crisp `1px solid #E6E1D8` border, text `#1F1D1A`. Hover state transitions background to `#F4E3DA` with text `#B5532E`.
- **Text / Ghost:** Transparent surface with `#6B665E` text; active state sets background `#FAF8F4` and text `#1F1D1A`.

### Book Covers & Cards
- **Book Cover Display:** Strict 2:3 ratio. Subtle `4px` border radius with an internal `1px` inset border (`rgba(31, 29, 26, 0.06)`). Includes the 1–2px soft book-edge shadow.
- **Library Cards:** Solid `#FFFFFF` fill, `12px` radius, bordered by `1px solid #E6E1D8`. Contains cover thumbnail, Literata book title, author string in Inter secondary, and reading progress bar.

### Chips & Tags
- **Metadata Chips:** Pill-shaped (`rounded-full`), height `28px`, padding `0 12px`. Background `#FAF8F4`, border `1px solid #E6E1D8`, text `#6B665E`, Inter `label-md`.
- **Active / Filter Chips:** Background `#F4E3DA`, border `1px solid #B5532E`, text `#B5532E`, font weight 600.

### Input Fields & Controls
- **Search & Text Inputs:** Height `48px`, background `#FFFFFF`, border `1px solid #E6E1D8`, radius `8px`. Padding `0 16px`. Focus state shifts border color to `#B5532E` with no outer glow.
- **Checkboxes & Radios:** `20px × 20px`, `4px` border radius for checkboxes, circular for radios. Inactive: `1.5px solid #E6E1D8`, background `#FFFFFF`. Active: `#B5532E` fill with `#FFFFFF` inner tick mark or center dot. Touch target padded to `48px`.

### E-Reader-Specific Components
- **Reader Progress Bar:** Subtle `4px` track height, track color `#E6E1D8`, filled bar `#B5532E`. Rounded endpoints.
- **Annotation & Bookmark Sheet:** Slips up from the bottom (mobile) or right gutter (desktop). Background `#FFFFFF`, border `1px solid #E6E1D8`, radius `12px 12px 0 0` on mobile.
- **Floating Reading Bar (Thumb Control):** Detached navigation pill floating `16px` above bottom margin on mobile. Background `#FFFFFF`, bordered by `#E6E1D8`, featuring quick font size, chapter index, theme toggle, and bookmark triggers.
- **Theme Switcher Pill:** Four inline segmented circles (Paper `#FAF8F4`, Sepia `#F3E7D0`, Dark `#1B1A18`, OLED `#000000`), each `32px` diameter, encased in a `48px` clickable container, active state marked with a 2px terracotta border ring.