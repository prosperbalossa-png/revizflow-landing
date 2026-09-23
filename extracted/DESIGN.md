---
name: Clarity & Momentum
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
  on-surface-variant: '#3c4a42'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6c7a71'
  outline-variant: '#bbcabf'
  surface-tint: '#006c49'
  primary: '#006c49'
  on-primary: '#ffffff'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#4edea3'
  secondary: '#006c4e'
  on-secondary: '#ffffff'
  secondary-container: '#80f9c8'
  on-secondary-container: '#007353'
  tertiary: '#565e74'
  on-tertiary: '#ffffff'
  tertiary-container: '#9ba2bb'
  on-tertiary-container: '#31394d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#80f9c8'
  secondary-fixed-dim: '#62dcad'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#00513a'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-xs:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
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

This design system establishes an academic productivity sanctuary designed for high-performing students and lifelong learners. It blends **Minimalism** with restrained **Glassmorphism**, optimizing cognitive ease, focus, and sustained momentum. The visual tone balances clinical clarity with invigorating warmth—eliminating friction, academic anxiety, and digital noise.

### Audience & Mood
- **Target Audience:** College students, graduate candidates, and focused learners seeking structured focus, revision planning, spaced repetition, and frictionless habit tracking.
- **Emotional Response:** Calm mastery, clarity, focused energy, and forward velocity. The interface feels lightweight and air-filled, yet grounded and precise.
- **Style Direction:** Modern Minimalist Bento. Crisp canvas layouts, pristine border boundaries, featherweight emerald blurs, and polished surface hierarchies that frame study materials without distraction.

## Colors

The color palette centers on active focus and mental renewal. A crisp, high-luminance backdrop sets an ultra-clean base, balanced by slate and zinc neutrals for structured typography and boundary definition. Vibrant emerald drives actionable milestones and primary actions, while soft mint accents provide celebratory feedback and low-friction status highlights.

### Palette Architecture
- **Primary Accent (`#10B981` / Darker Shade `#059669`):** Represents momentum, retention, and completed study flow. Reserved for primary calls-to-action, active timers, streak indicators, and key focus states.
- **Secondary Accent (`#6EE7B7` / Light Tint `#A7F3D0`):** Expresses breathing room and positive progress. Deployed in secondary badges, subtle gradient blooms, active chip backgrounds, and progress bar fills.
- **Tertiary Dark (`#0F172A`):** Deep slate-zinc used for high-contrast headlines, active primary tab labels, and prominent data metrics.
- **Neutral Foundation (`#64748B`):** Cool slate tone that yields supporting metadata, outline borders, unfocused tabs, and secondary body copy.

### Functional Surfaces
- **Canvas Base:** `#FFFFFF` pure white for the core viewport.
- **Card Substrates:** `#F8FAFC` (slate-50) and translucent `#FFFFFFCC` for frosted overlays.
- **Subtle Stroke / Dividers:** `#E2E8F0` (slate-200) with 60–80% opacity for airy, crisp borders.

## Typography

Typography relies on Plus Jakarta Sans across all display, body, and interface roles to cultivate a modern, welcoming, and sharp academic presence. Large geometry and open counters maintain effortless scanning speeds across study timers, task matrices, flashcards, and syllabus outlines.

- **Headlines:** Set in 600 and 700 weights with negative tracking (`-0.02em`) on sizes above 20px for crisp editorial authority.
- **Body:** Set in 400 weight with relaxed line-heights (1.5x–1.6x) to preserve reading ease over long study sessions.
- **Labels & Numbers:** Numerals in timers, metrics, and streak tallies use tabular figures (`tnum`) to prevent jitter during countdowns and data updates.

## Layout & Spacing

Layouts follow a fluid bento-grid structure rooted in an 8px base rhythm. This accommodates dashboard widgets, daily revision schedules, flashcard decks, and focus timers side by side with purposeful spatial separation.

### Grid Architecture
- **Desktop (1200px+):** 12-column dynamic fluid grid with a maximum content container of 1360px, 20px (`1.25rem`) gutters, and 32px (`2rem`) outer canvas margins. Bento units snap cleanly to 3, 4, 6, 8, or 12-column modules.
- **Tablet (768px - 1199px):** 8-column layout with 16px gutters and 24px outer margins. Multi-metric bento rows collapse to double-column stacks.
- **Mobile (<768px):** 4-column layout with 12px (`0.75rem`) gutters and 16px (`1rem`) outer margins. Bento grids stack vertically into single-column cards.

### Spacing Rhythm
- **Internal Bento Padding:** Standard cards employ `space-lg` (24px) internally; compact widgets utilize `space-md` (16px).
- **Element Clustered Gaps:** Buttons, inline tags, and form fields consistently step between `space-xs` (4px) and `space-sm` (8px).

## Elevation & Depth

Visual hierarchy uses clean layering, subtle frosted translucent backplates, and emerald-tinted ambient shadows instead of heavy, opaque elevations. This approach keeps cards floating effortlessly without creating visual clutter.

### Surface Hierarchy
- **Level 0 (Base Canvas):** Solid `#FFFFFF` or subtle neutral tint `#F8FAFC`.
- **Level 1 (Bento Cards & Content Modules):** Solid `#FFFFFF` or translucent `#FFFFFFEE` layered over ambient background accents. Framed with a 1px border of `rgba(226, 232, 240, 0.75)`.
  - **Shadow:** `0px 4px 20px -2px rgba(16, 185, 129, 0.05), 0px 1px 3px rgba(15, 23, 42, 0.03)`
- **Level 2 (Hovered Cards & Dropdowns):** Subtle upward translation (-2px) accompanied by an expanded tinted spread.
  - **Shadow:** `0px 12px 28px -4px rgba(16, 185, 129, 0.08), 0px 4px 8px -2px rgba(15, 23, 42, 0.04)`
  - **Border:** `rgba(16, 185, 129, 0.25)`
- **Level 3 (Modals, Overlays, Focus Sessions):** Frosted glass canvas backdrop (`backdrop-filter: blur(16px)` with `rgba(255, 255, 255, 0.85)` fill) paired with a deep, ultra-soft shadow:
  - **Shadow:** `0px 24px 48px -12px rgba(15, 23, 42, 0.12), 0px 8px 16px -4px rgba(16, 185, 129, 0.06)`

### Glassmorphism Treatment
Glass effects are applied exclusively to sticky navigation headers, command bars, floating audio/timer controls, and modal backdrop scrims. Surfaces use a background blur of `12px` to `20px` paired with a 1px boundary stroke of `rgba(255, 255, 255, 0.8)` for a crisp edge.

## Shapes

The design system employs a refined, rounded geometric profile (`roundedness: 2`). This choice softens analytical student dashboards while preserving structural alignment across dense data matrices and calendars.

- **Base Components (Inputs, Buttons, Cards):** Standard components use `0.5rem` (8px) to `0.75rem` (12px) corners.
- **Bento Modules:** Primary bento cards use `rounded-xl` (`1.25rem` / 20px) to establish clean, standalone modular groupings.
- **Badges, Status Chips, & Pill Controls:** Complete circular rounding (`rounded-full` / 9999px) is applied to revision status tags, streak counters, Pomodoro mode switches, and quick filters.

## Components

### Buttons
- **Primary Action:** Solid vibrant emerald (`#10B981`) fill, text in pure white (`#FFFFFF`), bold typography (`label-lg`), with subtle shadow `0 2px 8px rgba(16, 185, 129, 0.3)`. Hover state darkens slightly to `#059669` with a subtle 1px uplift.
- **Secondary Action:** Mint-tinted surface (`#ECFDF5`), emerald text (`#059669`), zero border. Hover transitions to `#D1FAE5`.
- **Ghost / Tertiary:** Slate text (`#64748B`), transparent background. Hover displays slate-50 (`#F8FAFC`) with primary slate text (`#0F172A`).
- **Focus Timer Pill Button:** Full pill contour (`rounded-full`), emerald fill with soft breathing glow indicator during active study intervals.

### Badges & Pill Chips
- **Status Tags:** Pill geometry (`rounded-full`) with `space-xs` vertical and `space-sm` horizontal padding.
  - *Active / On Track:* `#ECFDF5` background, `#059669` text, `#A7F3D0` soft border.
  - *Due Soon:* `#FFFBEB` background, `#D97706` text, `#FDE68A` soft border.
  - *Archived / Idle:* `#F1F5F9` background, `#64748B` text, `#E2E8F0` soft border.
- **Interactive Filter Chips:** Soft rounded-full toggles. Unselected state is white with slate-200 borders; selected state transitions to `#10B981` text with `#ECFDF5` background and `#6EE7B7` border.

### Bento Cards
- Clean pure white (`#FFFFFF`) or frosted translucent panels with uniform 1px slate-200 outline borders.
- Header zone houses a clear category label (`label-xs` uppercase in slate-400), primary title (`title-md`), and optional top-right pill badge.
- Inner padding fixed at `1.5rem` (desktop) and `1rem` (mobile).

### Inputs & Search Bars
- Background set to `#FFFFFF` with `#E2E8F0` border and `0.5rem` radius. Placeholder text rendered in muted slate-400.
- **Focused State:** 1px ring in `#10B981` accompanied by a `0 0 0 3px rgba(16, 185, 129, 0.15)` aura. No aggressive hard outlines.
- Global study search bar uses glassmorphic styling (`#FFFFFFBF` with `backdrop-filter: blur(8px)`) and a keyboard shortcut tag (`⌘K`) aligned to the right.

### Checkboxes & Task Rows
- Task items feature custom 20px rounded checkboxes (`rounded-md`, 6px corner radius).
- Unchecked: 1.5px border `#CBD5E1` against a clean white canvas.
- Checked: `#10B981` solid fill with an animated crisp white checkmark icon. Associated study task text smoothly transitions to slate-400 with a subtle strikethrough.

### Spaced-Repetition Flashcard Deck
- Stacked presentation showing multi-layer card depth behind the active card using scale transforms (`scale(0.96)`, `scale(0.92)`) and descending opacities.
- Active card features Level 2 elevation, generous 32px padding, centered typography, and mint-tinted flip/difficulty feedback buttons along the lower boundary.