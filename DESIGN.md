---
name: Fig & Filter
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#24221c'
  on-tertiary: '#ffffff'
  tertiary-container: '#393731'
  on-tertiary-container: '#a4a098'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#e7e2d9'
  tertiary-fixed-dim: '#cbc6bd'
  on-tertiary-fixed: '#1d1b16'
  on-tertiary-fixed-variant: '#494640'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  canvas-base: '#FAF6F0'
  surface-card: '#FFFFFF'
  surface-cream: '#F5EFE6'
  border-subtle: '#E8DFD5'
  text-muted: '#7A7274'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 3.5rem
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: '1.25'
    letterSpacing: '0'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: '0'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.65'
    letterSpacing: '0'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.06em
  price:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-desktop: 2rem
  margin: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

The design system embodies an artisanal, neighbourhood café aesthetic: grounded, honest, unpretentious, and quietly confident. It balances tactile culinary warmth with editorial discipline. The UI evokes the sensorial calm of stepping off a damp street into a warm room that smells of roasted Ethiopian beans, butter laminations, and parchment paper.

The audience encompasses two primary mindsets: a stranger clutching a mobile phone seeking immediate practical sanctuary (opening hours, address, vibe) and an office manager on a desktop evaluating catering with practical scrutiny. 

### Design Philosophy
- **Artisanal Minimalism with Editorial Warmth:** High-contrast text hierarchies, generous organic negative space, crisp hairline borders reminiscent of bespoke print ephemera, and intentional restraint.
- **Tone of Voice:** Warm, plainspoken, dry-humoured, and direct. No corporate buzzwords or generic hospitality clichés.
- **Focal Discipline:** Single-column mobile-first structure with exactly one primary visual call to action per page. Supporting navigation remains discreet and functional.

## Colors

The palette draws directly from the roasting drum and fig orchard, grounded by warm, non-sterile paper tones.

### Roles & Strict Usage Rules
- **Primary (`#4A2C4D` — Deep Fig Purple):** Used for solid primary buttons, authoritative display headings, key brand accents, and prominent badge backgrounds. Conveys depth and quiet craftsmanship.
- **Secondary / Accent (`#D9A441` — Warm Amber):** Reserved strictly for interactive visual highlights, focal tags, rating stars, and focused call-to-action details. **Never use `#D9A441` for body copy, paragraph text, or low-contrast text elements.**
- **Neutral Canvas (`#FAF6F0` — Warm Off-White):** The foundational page canvas backdrop. It avoids the harsh glare of pure `#FFFFFF` and provides a tactile, printed-paper texture feel.
- **Surfaces (`#FFFFFF` & `#F5EFE6`):** Card containers and structured sections sit on pure white or warm cream, establishing layered elevation without heavy synthetic drop shadows.
- **Text & Borders (`#221E1F`, `#7A7274`, `#E8DFD5`):** Text hierarchy relies on near-black `#221E1F` for supreme readability, paired with `#7A7274` for metadata, opening hours secondary labels, and prices. Structural division uses hairline borders tinted with `#E8DFD5`.

## Typography

The typographical pairing unites **Playfair Display** (a serif with editorial presence, warmth, and culinary character) with **Plus Jakarta Sans** (a modern, humanist sans-serif optimized for legibility across digital viewports).

### Hierarchy & Application Rules
- **Editorial Headings:** All section headings, hero statements, and package names use `Playfair Display`. The italic variant may be used sparingly for short tagline flourishes or founder quotes.
- **Legibility & Functional Data:** Menu items, prices, opening hours, transit notes, and buttons use `Plus Jakarta Sans` to guarantee split-second scanning on handheld devices.
- **Numbers & Prices:** Menu prices utilize `price` token (`Plus Jakarta Sans` semi-bold) aligned flush right or directly following item titles with clean tabular spacing.
- **Dietary Indicators:** Markers (e.g., `V`, `VG`, `GF`) use uppercase `label-sm` with slight tracking, enclosed in compact pill outlines or subtle badges.

## Layout & Spacing

The layout is built mobile-first, adhering to an intentional single-column reading experience on mobile devices and expanding up to a maximum 2-column or 3-column layout on wide screens.

### Grid & Breakpoints
- **Mobile (< 768px):** Strict 1-column layout. Max container width: 100%. Margins: `1.25rem` (`space-md` + `space-xs`).
  - Home hero info, Menu items, and Visit table stay above fold thresholds without excessive vertical padding.
- **Desktop (≥ 768px and up to 1080px max content width):**
  - **Menu:** Max 2 columns for quick scanning without eye-fatigue.
  - **Catering:** 3-column comparative cards side-by-side.
  - **Visit:** 2 columns (Left: hours table & address; Right: exterior photography and transit notes).
- **Rhythm & Safe Heights:**
  - On the **Visit** and **Home** mobile viewports, the café address ("8 Chalk Lane") and operational hours must be immediately visible above 640px vertical height without requiring scrolling.

## Elevation & Depth

To maintain an authentic artisanal feel, the design system rejects harsh drop shadows and neon lighting effects in favor of paper-like physical layering and structural hairline borders.

### Surface Hierarchy
- **Base Canvas:** Flat `#FAF6F0`.
- **Raised Surfaces (Cards, Tables, Modals):** Tinted `#FFFFFF` or `#F5EFE6` bound by a solid `1px` border of `#E8DFD5`.
- **Soft Ambient Separation:** When an element must float (such as mobile fixed navigation or sticky bottom CTA banners), apply an ultra-subtle tinted shadow:
  - `box-shadow: 0 4px 20px -2px rgba(74, 44, 77, 0.06), 0 2px 6px -1px rgba(34, 30, 31, 0.04)`
- **Divider Hairlines:** Used between menu groups and opening hours rows: `1px solid #E8DFD5`.

## Shapes

The system uses a soft, crafted geometry (`roundedness: 1` — base border radius `0.25rem` / `4px`), reflecting traditional printed menus and tactile stationery rather than overly bubbly app widgets.

### Shape Scale
- **Base Components (Inputs, Cards, Menu Containers):** `0.25rem` (soft, crisp cornering).
- **Large Cards & Images (`rounded-lg`):** `0.5rem` (8px), used on founder portraits and catering comparison cards.
- **Badges & Dietary Tags:** Fully rounded pill shapes (`9999px`) provide contrast against the rectangular structural cards.

## Components

### 1. Primary Call-to-Action (Single CTA Rule)
Every page supports strictly **one** primary call to action.
- **Appearance:** Solid `#4A2C4D` background with `#FAF6F0` text, `0.25rem` radius, padding `0.875rem 1.75rem`, font `label-md`. 
- **Hover/Active:** Background shifts to `#381F3B` with a subtle amber accent underline or hairline focus ring in `#D9A441`.
- **Secondary Links:** Styled as plain textual links (`#221E1F` with a clean `1px` underline in `#7A7274`) to prevent visual conflict with the primary CTA.

### 2. Menu Item Row
- **Structure:** Flexible row with Item Name and Dietary Tag on the left, dotted or clean empty leader line, and Price on the right.
- **Typography:** Name in `Plus Jakarta Sans` 600, short description in `body-sm` (`#7A7274`), Price in `price` (`#221E1F`).
- **Dietary Indicators:** Compact inline tags (`V`, `VG`, `GF`) styled with `0.125rem 0.375rem` padding, background `#F5EFE6`, text `#4A2C4D`, font `label-sm`.

### 3. Catering Comparison Cards
- **Structure:** Contained cards with `#FFFFFF` background, `1px solid #E8DFD5` border, and `1.5rem` padding.
- **Featured Tier ("The Morning Tea"):** Highlighted by an accent badge at the top ("Most Popular") filled with `#D9A441` (text `#221E1F`, font `label-sm`) and an outline border of `#4A2C4D`.
- **Package Pricing:** Displayed prominently as `$X / person` using `Playfair Display` 2rem.

### 4. Opening Hours & Info Table
- **Layout:** Two-column tabular list. Days flush left (`#221E1F`, font `body-md`), hours flush right (`#7A7274`, font `body-md`).
- **Dividers:** Crisp horizontal `1px solid #E8DFD5` rules separating days. "Monday: Closed" highlighted in muted italic tone.

### 5. Persistent Footer
Rendered uniformly across all five pages:
- **Background:** `#F5EFE6` with top border `1px solid #E8DFD5`.
- **Content Blocks:**
  1. Brand Name & Tagline ("Fig & Filter — Roasted here. Baked here. Poured for you.").
  2. Location & Hours: "8 Chalk Lane (corner Weaver St) · Tue–Sun 7:30am–5:00pm".
  3. Contact: Email link with plain styling.
  4. Catering Link: "Order catering →" rendered as a refined secondary action.