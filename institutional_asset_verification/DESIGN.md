---
name: Institutional Asset Verification
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#434655'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747686'
  outline-variant: '#c4c5d7'
  surface-tint: '#2151da'
  primary: '#0037b0'
  on-primary: '#ffffff'
  primary-container: '#1d4ed8'
  on-primary-container: '#cad3ff'
  inverse-primary: '#b7c4ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#004870'
  on-tertiary: '#ffffff'
  tertiary-container: '#006194'
  on-tertiary-container: '#b2d9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b5'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.025em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Geist
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Geist
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.005em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the rigor, fiduciary gravity, and technical precision demanded by institutional finance, custodian banks, and asset managers verifying real-world assets (RWA). It avoids retail Web3 tropes, fluorescent accents, and speculative motifs, establishing authority through balanced proportion, structural transparency, and data density.

The aesthetic fuses modern enterprise minimalism with high-precision technical tooling. Interfaces evoke the calm confidence of financial infrastructure: structured grids, controlled typography, crisp borders, and purposeful contrast ratios that adhere to WCAG AAA accessibility guidelines.

## Colors

The palette is engineered for visual endurance, legibility, and uncompromising hierarchy across dense data layouts.

- **Canvas & Surfaces:**
  - Base Background: `#F8FAFC` (Slate 50)
  - Surface Pure: `#FFFFFF` (White)
  - Surface Muted: `#F1F5F9` (Slate 100)
  - Surface Subdued: `#E2E8F0` (Slate 200)

- **Text & Content Hierarchy:**
  - Dominant Text / Primary: `#0F172A` (Slate 900)
  - Secondary Content / Labels: `#334155` (Slate 700)
  - Muted Metadata / Placeholders: `#64748B` (Slate 500)
  - Disabled Elements: `#94A3B8` (Slate 400)

- **Brand & Action Signals:**
  - Primary Steel Accent: `#1D4ED8` (Blue 700)
  - Primary Hover: `#1E40AF` (Blue 800)
  - Primary Subtle / Selection Background: `#EFF6FF` (Blue 50)
  - Primary Border Focus: `#3B82F6` (Blue 500)

- **System & Compliance States:**
  - Success / Attested: `#047857` (Emerald 700) with surface `#ECFDF5` (Emerald 50) and border `#A7F3D0`
  - Warning / Verification Pending: `#B45309` (Amber 700) with surface `#FFFBEB` (Amber 50) and border `#FDE68A`
  - Critical / Failed Audit: `#B91C1C` (Red 700) with surface `#FEF2F2` (Red 50) and border `#FECACA`
  - Informational / Escrow Active: `#0369A1` (Sky 700) with surface `#F0F9FF` (Sky 50) and border `#BAE6FD`

## Typography

The type system blends structural geometric precision from Geist with the optimized screen legibility of Inter. 

- Use **Geist** for high-level analytical displays, primary view titles, and numerical/token identifiers requiring tabular precision.
- Use **Inter** for all narrative UI components, instructional metadata, forms, inputs, and dense transaction ledgers.
- Set `font-feature-settings: "cv02", "cv03", "cv04", "cv11", "tnum"` globally to enforce tabular numeric alignment across all currency values, balance sheets, and transaction hash displays.

## Layout & Spacing

Layouts adhere to an 8px base rhythm (with a 4px half-step for micro-alignment within compact data tables and badges).

- **Grid Architecture:** Desktop views operate on a 12-column responsive fluid grid inside a 1440px maximum container. Outer canvas margins are 32px (`margin`), with 24px column gutters (`gutter`). For complex verification dashboards, widescreen viewports (1920px+) expand fluidly with fixed 280px left navigation panels.
- **Breakpoints:**
  - Mobile (`< 768px`): Single column layout, 16px page margins (`margin-sm`), 16px element gutters (`gutter-sm`).
  - Tablet (`768px - 1024px`): 8-column layout, 24px margins, 16px gutters.
  - Desktop (`> 1024px`): 12-column layout, 32px margins, 24px gutters.
- **Vertical Rhythm:** Component groupings retain strict spacing discipline. Inner-card element padding is uniformly 16px (`space-md`) or 24px (`space-lg`), while sectional content divisions scale by 40px (`space-xl`).

## Elevation & Depth

This design system avoids theatrical drop shadows and floating skeuomorphic planes. Visual hierarchy is established through surface luminance layering, fine structural borders, and neutral ambient shadows.

- **Base Level (Canvas):** `#F8FAFC` flat surface. No shadow.
- **Surface Level 1 (Panels, Tables, Cards):** Background `#FFFFFF` with a 1px border of `#E2E8F0`. Shadow: `0px 1px 2px 0px rgba(15, 23, 42, 0.05)`.
- **Surface Level 2 (Dropdowns, Popovers, Filter Menus):** Background `#FFFFFF` with a 1px border of `#CBD5E1`. Shadow: `0px 4px 6px -1px rgba(15, 23, 42, 0.08), 0px 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Surface Level 3 (Modal Dialogs, Verification Drawers):** Background `#FFFFFF` with a 1px border of `#CBD5E1`. Shadow: `0px 20px 25px -5px rgba(15, 23, 42, 0.1), 0px 8px 10px -6px rgba(15, 23, 42, 0.04)`. Accompanied by backdrop overlay `rgba(15, 23, 42, 0.45)` with a 2px backdrop blur.

## Shapes

Corner radii communicate structural discipline and industrial precision.

- **Primary Geometry:** Standard interface objects (buttons, text inputs, cards, notification banners) use a uniform 8px radius (`0.5rem`).
- **Containers & Modals:** Large dashboard cards, modals, and slide-over verification drawers utilize a 12px radius (`0.75rem`).
- **Micro-Elements:** Compliance tags, status indicators, and audit chips use a 4px to 6px radius to maintain sharp readability without visual clutter. Circular pills are strictly limited to numeric quantity badges.

## Components

### Buttons
- **Primary:** Solid `#1D4ED8` background, `#FFFFFF` text, 8px radius, `h-10` (40px) or `h-9` (36px). Hover: `#1E40AF`. Active: `#1E3A8A`. Focus ring: 2px `#3B82F6` with 2px offset.
- **Secondary / Outline:** Background `#FFFFFF`, 1px border `#CBD5E1`, text `#0F172A`. Hover: `#F8FAFC` with border `#94A3B8`.
- **Ghost:** Transparent background, text `#334155`. Hover: `#F1F5F9`, text `#0F172A`.
- **Destructive:** Solid `#DC2626` background, `#FFFFFF` text. Hover: `#B91C1C`.

### Compliance & Status Badges
- Institutional verification tags consist of a subtle tinted container, an explicit 1px border, a solid 6px status dot, and uppercase tracking `label-sm` text.
  - *Attested / On-Chain:* Background `#ECFDF5`, border `#A7F3D0`, text `#047857`.
  - *Pending Verification:* Background `#FFFBEB`, border `#FDE68A`, text `#B45309`.
  - *Audit Flagged:* Background `#FEF2F2`, border `#FECACA`, text `#B91C1C`.

### Cards & Data Panels
- Background `#FFFFFF`, 1px border `#E2E8F0`, 8px to 12px radius.
- Headers feature a bottom border `#F1F5F9` separating meta titles from primary KPI data.
- Hover interactions on selectable records shift the border to `#94A3B8` with an inset 2px indicator bar of `#1D4ED8` on the leading edge.

### Input Fields & Controls
- **Text Inputs:** Height 40px, 8px radius, background `#FFFFFF`, border 1px `#CBD5E1`, text `#0F172A`, placeholder `#94A3B8`. Focus state applies a 1px border `#1D4ED8` and `box-shadow: 0 0 0 1px #1D4ED8`.
- **Checkboxes & Radios:** 16x16px footprint, 4px radius for checkboxes, full circle for radios. Border 1px `#CBD5E1`. Checked state: background `#1D4ED8`, border `#1D4ED8`.

### Data Tables & Verification Ledgers
- Headers: Background `#F8FAFC`, uppercase `label-sm` font in `#475569`, 1px bottom border `#E2E8F0`.
- Cells: Vertical padding 12px, horizontal padding 16px, 1px bottom border `#F1F5F9`.
- Numeric values, contract addresses, and transaction hashes render strictly in tabular font variants with copy-to-clipboard interactions.