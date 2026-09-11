---
name: Precision Utility
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
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006c4a'
  on-secondary: '#ffffff'
  secondary-container: '#82f5c1'
  on-secondary-container: '#00714e'
  tertiary: '#824500'
  on-tertiary: '#ffffff'
  tertiary-container: '#a65900'
  on-tertiary-container: '#ffede1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.005em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  container-max: 72rem
---

## Brand & Style

This design system delivers a fast, privacy-first, and highly reliable document productivity environment. Designed for knowledge workers, legal operations, students, and enterprise staff, the interface balances utilitarian speed with corporate refinement. It evokes zero hesitation: users feel that processing high-stakes documents is safe, instantaneous, and deterministic.

The visual direction follows **Corporate / Modern** precision combined with hyper-clean utilitarian minimalism:
- Pure clarity over decoration: Every visual affordance directly corresponds to a functional file operation.
- Immediate spatial feedback: Drop zones, processing pipelines, and file rosters use precise states rather than ambient novelty.
- High operational density: High information clarity that handles complex multipage arrangements, batch conversion lists, and granular page controls without visual clutter.

## Colors

The palette uses high-clarity royal blue for primary actions and file state tracking, complemented by an emerald confirmation system that provides positive reinforcement when operations finalize.

### Palette Architecture
- **Primary (`#2563EB`)**: Anchor color for primary interaction triggers, active drag-over boundaries, selection ranges, and linear progress meters. Deepens to `#1D4ED8` on hover and `#1E40AF` on press.
- **Secondary (`#059669`)**: Reserved strictly for validated states—task completion indicators, successful signature locks, download-ready badges, and healthy file verification rings.
- **Tertiary (`#D97706`)**: High-visibility warning accent for destructive or lossy workflows: PDF page removal, file size limit warnings, password removal alerts, and compression loss thresholds.
- **Neutral (`#64748B`)**: Modern slate spectrum delivering balance without the harshness of neutral charcoal:
  - App Canvas Base: `#F8FAFC`
  - Elevated Tile/Workspace: `#FFFFFF`
  - Hairline Structural Borders: `#E2E8F0`
  - De-emphasized Metadata/File Specs: `#64748B`
  - High-Contrast Headlines and Filenames: `#0F172A`

## Typography

The type system prioritizes legibility at compact scales. Variable numeric tabular figures (`tnum`) must be enforced across page counters, byte sizes, and elapsed compression timers.

- **Headlines**: Tight negative tracking (`-0.015em` to `-0.025em`) creates crisp visual structure for tool headings, modal headers, and utility hero intros.
- **Body**: Clean neutral vertical rhythm at 14px/20px for operational instructions, settings panels, and batch file summaries.
- **Data & Micro-Labels**: Uppercase 11px/12px elements (e.g., `PDF`, `A4`, `300 DPI`, `12.4 MB`) employ `JetBrains Mono` or `Inter` with medium weights and slight positive tracking for fast visual scanning.

## Layout & Spacing

A centralized 12-column fixed/fluid hybrid system maximizes single-task focus while accommodating broad batch-processing matrices.

### Breakpoints & Geometry
- **Desktop (1280px+)**: 12-column grid; 24px gutters; maximum content container width of 1152px (`72rem`) to eliminate peripheral eye strain during detailed file configuration.
- **Tablet (768px - 1279px)**: 8-column layout; 20px gutters; side-by-side workspace drops to split-pane orientation.
- **Mobile (320px - 767px)**: 4-column layout; 16px margins; drag-and-drop landing areas reconfigure into full-width target taps with sticky conversion bottom sheets.

### Workspace Rhythms
- Active utility canvas relies on standard `4px` / `8px` increments.
- File upload staging zones enforce minimum target heights: 280px on desktop and 180px on mobile.
- Multipage thumbnail grids align to standard 140px-wide card slots with dynamic horizontal auto-fill.

## Elevation & Depth

Visual depth is achieved through layered white card surfaces set against the `#F8FAFC` foundation, reinforced with dual-layer ambient shadows tinted with neutral slate.

### Shadow Tiers
- **Surface Tier 0 (Canvas)**: `#F8FAFC` (Flat, no shadow).
- **Surface Tier 1 (Stationary Cards & Modules)**: Pure `#FFFFFF` surface with border `1px solid #E2E8F0` and `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Surface Tier 2 (Hoverable File Tiles & Floating Toolbars)**: `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Surface Tier 3 (Modals, Active Dragged Items & Dropdown Drawers)**: `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`.

### Interaction Overlays
- Active drag-over states apply an animated hairline boundary: `2px dashed #2563EB` with an internal tint overlay of `#EFF6FF` (Blue-50 at 60% opacity).
- Pages dragged within reordering canvases scale to `1.03` with a Tier 3 elevation and 35% blue-tinted drop halo.

## Shapes

The design uses a clean `roundedness: 1` structure. This soft geometry balances approachability with technical precision:

- Small interactive targets (inputs, secondary buttons, tags, status pills): `rounded` (4px to 6px).
- Utility cards, upload zones, preview sheets, and dialogs: `rounded-lg` (8px).
- Modal wrappers and parent dashboard canvases: `rounded-xl` (12px).
- Rounded pill exceptions (`rounded-full`) are reserved exclusively for circular action controls (page rotate buttons, item removal triggers) and numerical sequence badges.

## Components

### Buttons
- **Primary**: Solid `#2563EB` background, white text, 8px corner radius, font-weight 600. States: hover `#1D4ED8`, active `#1E40AF`, focus 2px ring `#93C5FD` with 2px offset.
- **Secondary / Ghost**: High-contrast white background, 1px solid border `#CBD5E1`, text `#1E293B`. Hover: `#F1F5F9` background, border `#94A3B8`.
- **Destructive**: Subdued white card with red outline `#FCA5A5` and text `#DC2626`. Hover: solid `#DC2626` with white text.

### Drop & Processing Zones
- Base idle state: Solid `#FFFFFF` background with 2px dashed border `#CBD5E1`. Centered icon badge (48px slate circle with royal blue icon).
- Hover / File Dragged Over: Border shifts to 2px dashed `#2563EB`, background transitions to `#F0F7FF`.
- Uploading/Processing State: Border transitions to solid `#E2E8F0`, displaying a centered linear striped progress bar in `#2563EB` with percentage indicators.

### Document Preview Cards
- Form factor: Compact A4 ratio frame with an off-white internal preview sheet, framed by 1px solid border `#E2E8F0`.
- Hover Controls: Floating pill menu anchored to the top-right corner with 32px circular buttons for "Rotate Left", "Rotate Right", and "Delete".
- Status Badge: Bottom-left anchored badge showing format (`PDF`, `PNG`) and sequential page marker (`Page 01`).

### Status Badges & Chips
- **Success / Ready**: Light emerald background `#ECFDF5`, text `#065F46`, 1px solid border `#A7F3D0`. Includes a 6px solid emerald dot.
- **Processing / Active**: `#EFF6FF` background, `#1E40AF` text, with an inline micro-spinner.
- **Warning / Over-size**: `#FFFBEB` background, text `#92400E`, border `#FDE68A`.

### Inputs & Sliders
- Text/Password inputs: Height 40px, 1px border `#CBD5E1`, background `#FFFFFF`, text `#0F172A`. Focused: border `#2563EB`, outer ring 3px `#DBEAFE`.
- PDF Range Sliders (Compression/Quality control): 6px height slate track `#E2E8F0`, active fill `#2563EB`, 18px circular thumb with white center and drop shadow.