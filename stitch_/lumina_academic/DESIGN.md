---
name: Lumina Academic
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
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#712ae2'
  on-secondary: '#ffffff'
  secondary-container: '#8a4cfc'
  on-secondary-container: '#fffbff'
  tertiary: '#4b1c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e2d00'
  on-tertiary-container: '#ff8f4f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#eaddff'
  secondary-fixed-dim: '#d2bbff'
  on-secondary-fixed: '#25005a'
  on-secondary-fixed-variant: '#5a00c6'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#783200'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
  success-emerald: '#10B981'
  error-rose: '#F43F5E'
  surface-bg: '#F8FAFC'
  points-gold: '#FACC15'
typography:
  display-balance:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  max-width: 1280px
---

## Brand & Style

The brand personality is **Structured, Encouraging, and Authoritative**. It bridges the gap between high-stakes educational management and the engaging feedback loops of gamification. The target audience includes students and academic administrators who require a platform that is reliable enough for auditing but vibrant enough to motivate daily progress.

The design style is **Corporate / Modern with Tonal Depth**. It leverages a rigorous grid system and clear information hierarchy typical of enterprise SaaS, while using vibrant accents and layering to denote gamified rewards and status. The interface prioritizes data integrity and legibility, using "Glassmorphism" selectively for floating elements like confirmation modals to maintain a sense of lightness and modernity.

## Colors

The palette is built on a foundation of **Deep Trust (Blue)** and **Energetic Progression (Purple/Orange)**. 

- **Primary (Deep Blue):** Used for structural navigation, headers, and primary administrative actions. It evokes stability and academic rigor.
- **Secondary (Vibrant Purple):** Used for "Level Up" states, leaderboard highlights, and personal achievements. It represents the "premium" nature of gamified success.
- **Tertiary (Bright Orange):** Specifically reserved for point accrual, "Coming Soon" badges, and call-to-action triggers that require immediate visual attention.
- **Neutral (Slate):** Handles the bulk of the UI's secondary information, borders, and empty states.
- **Color Mode:** The default mode is `light`, utilizing a soft grey-blue surface (`#F8FAFC`) to reduce eye strain during long-form data entry while maintaining high contrast for text.

## Typography

The typography system prioritizes clarity and a "Modern Tech" aesthetic. 

- **Hanken Grotesk** is used for headlines and labels to provide a sharp, contemporary edge that feels professional yet approachable. 
- **Inter** is the workhorse for body copy and data-heavy lists, chosen for its exceptional legibility at small sizes.
- **JetBrains Mono** is utilized specifically for the "Points Ledger" and Audit IDs in the Admin Panel to differentiate system-generated logs from user-generated content.
- **Mobile Scaling:** For displays larger than 32px (like the `display-balance`), font sizes should scale down by 25% on mobile devices (320px - 480px) to ensure the balance remains on a single line.

## Layout & Spacing

This design system uses a **Fixed Grid** philosophy for desktop to maintain structural integrity, transitioning to a **Fluid Grid** for mobile devices.

- **Desktop (1024px+):** 12-column grid with a max-width of 1280px. Gutters are fixed at 24px.
- **Tablet (768px - 1023px):** 8-column grid with 20px gutters. 
- **Mobile (320px - 767px):** 4-column fluid grid. Margins are 16px. Components like the Point Balance card must span the full width of the container.
- **Rhythm:** All spacing (padding, margins, gap) must be multiples of the 4px base unit to create a predictable visual cadence.

## Elevation & Depth

Visual hierarchy is managed through **Tonal Layering** supplemented by **Ambient Shadows** for interactive elements.

1.  **Base Layer:** The surface-bg (`#F8FAFC`) acts as the canvas.
2.  **Surface Tier:** Cards and list containers use a white background with a subtle 1px border (`#E2E8F0`) and no shadow to appear "embedded" in the page.
3.  **Raised Tier:** Interactive components like hover-state buttons or active list items receive a soft, low-opacity shadow (4% opacity, 8px blur, tinted with the primary blue).
4.  **Overlay Tier:** Modals and tooltips utilize a frosted-glass effect (Backdrop Blur: 12px) with a more pronounced shadow to separate them from the underlying data management tasks.

## Shapes

The shape language is **Rounded (0.5rem)**, striking a balance between the friendliness of gamification and the professional structure of an educational platform.

- **Standard Elements:** Buttons, input fields, and cards use the base 0.5rem (8px) radius.
- **Large Containers:** Dashboard widgets and sections use `rounded-lg` (1rem / 16px).
- **Status Pills:** "Coming Soon" badges and point categories use `rounded-xl` (1.5rem) or a full pill shape to distinguish them from functional inputs.

## Components

- **Buttons:** Primary buttons use a solid Deep Blue fill. Achievement-related buttons use a Secondary Purple gradient. All buttons have a 200ms transition on hover with a slight elevation increase.
- **Cards:** Used for the "Personal Cabinet" balance. The balance card should feature a subtle gradient background (Primary to Secondary) to feel like a "Reward" space.
- **Input Fields:** Search fields must have a clear "3-character" helper text. The text area for manual accrual reasons must include a live character counter (5-200).
- **Chips & Badges:** "Coming Soon" badges use a Tertiary Orange stroke with a 10% opacity fill of the same color. 
- **Leaderboard Rows:** Rows should use alternating zebra-striping or a subtle border-bottom. The top 3 users should feature a small icon (Gold/Silver/Bronze star) next to their rank.
- **Modals:** Confirmation modals for manual point accrual must have a high-contrast "Confirm" button (Primary) and a "Cancel" text-link to prevent accidental points injection.
- **Empty States:** Use a custom slate-colored illustration for the "Empty Leaderboard" to maintain the professional aesthetic while acknowledging the lack of data.