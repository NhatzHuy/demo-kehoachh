---
name: DevStudy Hub
colors:
  surface: '#0c1324'
  surface-dim: '#0c1324'
  surface-bright: '#33394c'
  surface-container-lowest: '#070d1f'
  surface-container-low: '#151b2d'
  surface-container: '#191f31'
  surface-container-high: '#23293c'
  surface-container-highest: '#2e3447'
  on-surface: '#dce1fb'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dce1fb'
  inverse-on-surface: '#2a3043'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#c0c1ff'
  on-secondary: '#1000a9'
  secondary-container: '#3131c0'
  on-secondary-container: '#b0b2ff'
  tertiary: '#4cd7f6'
  on-tertiary: '#003640'
  tertiary-container: '#00b2d0'
  on-tertiary-container: '#003f4b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#acedff'
  tertiary-fixed-dim: '#4cd7f6'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5c'
  background: '#0c1324'
  on-background: '#dce1fb'
  surface-variant: '#2e3447'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
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
    lineHeight: 18px
    letterSpacing: 0.01em
  label-code-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: -0.01em
  label-code-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0em
  label-code-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

The design system is engineered for computer science and IT students balancing coursework, code sprints, lab deadlines, and algorithmic problem-solving. The design aesthetic is a precision-driven, high-tech dark interface that balances the focus of an IDE with the fluid productivity of a modern developer workspace.

The style fuses **Modern Minimalist Dev-Tech** with **Atmospheric Luminescence**. Visual weight relies on deep slate base planes, subtle grid lines, hairline borders, and targeted vibrant neon accents that mirror terminal status lights, compiler diagnostics, and code-syntax tokens.

The UI avoids extraneous decoration. Instead, it creates visual interest and communicates hierarchy through crisp contrast, monospaced data metadata, glowing micro-indicators, and structural panels that feel engineered, fast, and distraction-free.

## Colors

The palette establishes an authentic terminal and IDE environment optimized for extended night sessions without cognitive fatigue.

- **Background Planes**: Deepest canvas starts at `#020617` (Slate 950), stepping up to `#0f172a` (Slate 900) for nested zones, workspaces, and navigation rails.
- **Surfaces & Cards**: Component containers live at `#1e293b` (Slate 800) and `#182234` (Slate 850), bound by crisp structural borders at `#334155` (Slate 700) and translucent border overlays (`rgba(148, 163, 184, 0.12)`).
- **Primary Accent (`#10b981` Neon Emerald)**: Reserved for completed states, compilation success, passing tests, active focus timers, and primary action confirmation.
- **Secondary Accent (`#6366f1` / `#818cf8` Indigo/Violet)**: Used for active interactive states, selected navigation, subject categorization (e.g., Computer Systems, Algorithms), and progress milestones.
- **Tertiary Accent (`#06b6d4` Cyan)**: Applied to code snippets, Git branch pills, live metrics, micro-glows, and deadline tags.
- **Text & Foreground**: Highest contrast is reserved for titles using `#f8fafc` (Slate 50), readable body text at `#cbd5e1` (Slate 300), and de-emphasized metadata at `#64748b` (Slate 500).

## Typography

Typography pairs `Inter` for natural, highly legible interface communication and `JetBrains Mono` for all data-rich, structured, and developer-oriented contexts.

- **Primary Type (`Inter`)**: Governs structural titles, navigation links, subject names, assignment descriptions, and general narrative. High weights (`600`, `700`) use tight negative letter-spacing for an editorial, modern software tool feel.
- **Code & Metric Type (`JetBrains Mono`)**: Strict application across timestamps, progress ratios (e.g., `14/20 tasks`), commit hashes, course codes (e.g., `CS204`, `DSA-01`), keyboard shortcuts, status badges, and terminal blocks.
- **Hierarchy Standard**: Numeric indicators, countdown timers, and technical labels must always be rendered in `JetBrains Mono` to establish clear separation between narrative content and execution metadata.

## Layout & Spacing

The dashboard relies on an adaptable fluid grid with strict mathematical cadence derived from a 4px/8px modular scale.

- **Desktop (>= 1200px)**: A 12-column layout governed by a collapsible sidebar rail (64px icon-only or 240px expanded). Layout tracks with `margin-desktop: 2rem` and `gutter-desktop: 1.5rem`. Secondary utility sidebars (e.g., daily schedule or upcoming PRs/deadlines) remain pinned at 320px.
- **Tablet (768px – 1199px)**: Fluid 8-column system with `margin-tablet: 1.5rem` and `gutter: 1rem`. Primary workspace retains priority; auxiliary panels collapse into sliding bottom sheets or quick drawers.
- **Mobile (< 768px)**: Single column with `margin: 1rem` and `gutter: 1rem`. Task boards transition from horizontal multi-column kanbans into tabbed board views or stacked collapsible cards.
- **Component Rhythms**: `space-xs` (4px) separates icon-to-label pairs; `space-sm` (8px) separates tight group elements and badge padding; `space-md` (16px) establishes card internal padding; `space-lg` (24px) separates card headers from content bodies; and `space-xl` (32px) isolates major modular widgets.

## Elevation & Depth

Visual depth avoids heavy drop shadows, instead using **tonal layered surfaces**, **translucent hairline borders**, and **localized neon micro-glows**.

- **Level 0 (Canvas Base)**: Pure background (`#020617`), zero blur, non-elevated.
- **Level 1 (Card & Module Surfaces)**: Slate 850 (`#182234`) with a 1px solid hairline border in Slate 700 with 50% opacity (`rgba(51, 65, 85, 0.5)`). No drop shadow.
- **Level 2 (Hovered & Active Items)**: Surface steps up to Slate 800 (`#1e293b`). The border transitions to an illuminated state using `rgba(99, 102, 241, 0.4)` (Indigo) or `rgba(16, 185, 129, 0.4)` (Emerald), accompanied by a soft, diffused glow: `box-shadow: 0 0 16px -4px rgba(99, 102, 241, 0.25)`.
- **Level 3 (Modals, Command Palettes & Overlays)**: Surface sits at `#0f172a` with 80% opacity and `backdrop-filter: blur(12px)`. Outlined by a prominent boundary: `1px solid rgba(148, 163, 184, 0.2)`. Casts an ambient shadow: `0 20px 25px -5px rgba(0, 0, 0, 0.6), 0 8px 10px -6px rgba(0, 0, 0, 0.6)`.
- **Micro-Detail Glowing Points**: Unread notifications, active live timers, and build status pills use a small, pulsing glow aura (`0 0 8px currentColor`) to draw the eye without disrupting the dark-mode layout balance.

## Shapes

The design system maintains a **Soft-Tech (Level 1)** geometric geometry. This choice enforces a clean, software-native structure that complements technical dashboards and IDE-adjacent tools without feeling aggressive or clinical.

- **Base Corner Radius (`0.25rem` / 4px)**: Applied to micro-elements, status tags, checkboxes, input controls, and syntax code blocks.
- **Medium Corner Radius (`0.5rem` / 8px)**: Default for cards, standard action buttons, dropdown panels, and task items.
- **Large Corner Radius (`0.75rem` / 12px)**: Reserved for high-level module groups, modals, dialog panels, and command palette shells.
- **Pills**: Exclusively reserved for status dots with text (e.g., `• LIVE`, `• COMPILED`) and Git branch identification tags.

## Components

### Buttons
- **Primary (Accent)**: Background `#10b981` (Emerald), text `#020617` (bold `Inter`), `0.5rem` radius. On hover, lightens to `#34d399` with a subtle glow: `box-shadow: 0 0 14px rgba(16, 185, 129, 0.35)`.
- **Secondary (Tech Action)**: Background `#1e293b`, 1px border `#334155`, text `#f8fafc`. Hover triggers a border transition to `#6366f1` (Indigo) with text `#818cf8`.
- **Ghost / Code Button**: Borderless, text `#94a3b8`, monospaced accents. Hover applies `background: rgba(51, 65, 85, 0.3)`.

### Cards & Task Blocks
- Structured containers with a background of `#182234` and a 1px border of `#334155`.
- **Top Accent Line**: Cards can support a top 2px accent rule corresponding to status (e.g., cyan for In Progress, emerald for Completed, violet for Lab Assignment).
- Hover state transitions the border to `rgba(99, 102, 241, 0.5)` with an interior elevation lift.

### Input Fields & Command Prompts
- Background: `#0f172a` (Slate 900) inset with a 1px border of `#334155`.
- Active focus state: Border shifts to `#6366f1` with an interior ring glow `0 0 0 1px #6366f1`.
- Prefix indicators display terminal prompt symbols (e.g., `> `, `~ `) rendered in `JetBrains Mono` and styled in Cyan (`#06b6d4`).

### Badges & Technical Chips
- Low-opacity filled containers with crisp hairline outlines:
  - **Success / Passed**: `background: rgba(16, 185, 129, 0.1)`, `border: 1px solid rgba(16, 185, 129, 0.3)`, text `#10b981`.
  - **In Progress / Lab**: `background: rgba(99, 102, 241, 0.1)`, `border: 1px solid rgba(99, 102, 241, 0.3)`, text `#818cf8`.
  - **Urgent / Deadline**: `background: rgba(239, 68, 68, 0.1)`, `border: 1px solid rgba(239, 68, 68, 0.3)`, text `#f87171`.
- Text renders in `label-code-sm` (`JetBrains Mono`, uppercase, tracked out).

### Checkboxes & Task Toggles
- Custom square components (`18px x 18px`) with a `0.25rem` radius, bordered in `#475569`.
- Checked state transitions to a solid `#10b981` background featuring a slate-950 checkmark icon, immediately strikethrough-animating the associated task title.

### Study-Specific Components
- **Study Streak / Code Activity Grid**: Minimalist GitHub-style contribution squares utilizing 4 tiers of Emerald intensity (`#064e3b`, `#047857`, `#059669`, `#10b981`).
- **Pomodoro / Focus Terminal**: Compact module with a large monospaced countdown (`JetBrains Mono`), an active glowing ring indicator, and session markers (e.g., `[Sprint 02/04]`).
- **Course Snippet Card**: Shows course IDs (`CS301`), progress bars with dual-color gradients (Indigo to Cyan), and linked assignment tasks.