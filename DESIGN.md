---
name: Deep Intelligence Institutional System
colors:
  surface: '#141218'
  surface-dim: '#141218'
  surface-bright: '#3b383e'
  surface-container-lowest: '#0f0d13'
  surface-container-low: '#1d1b20'
  surface-container: '#211f24'
  surface-container-high: '#2b292f'
  surface-container-highest: '#36343a'
  on-surface: '#e6e0e9'
  on-surface-variant: '#cbc4d2'
  inverse-surface: '#e6e0e9'
  inverse-on-surface: '#322f35'
  outline: '#948e9c'
  outline-variant: '#494551'
  surface-tint: '#cfbcff'
  primary: '#cfbcff'
  on-primary: '#381e72'
  primary-container: '#6750a4'
  on-primary-container: '#e0d2ff'
  inverse-primary: '#6750a4'
  secondary: '#cdc0e9'
  on-secondary: '#342b4b'
  secondary-container: '#4d4465'
  on-secondary-container: '#bfb2da'
  tertiary: '#e7c365'
  on-tertiary: '#3e2e00'
  tertiary-container: '#c9a74d'
  on-tertiary-container: '#503d00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#cfbcff'
  on-primary-fixed: '#22005d'
  on-primary-fixed-variant: '#4f378a'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#cdc0e9'
  on-secondary-fixed: '#1f1635'
  on-secondary-fixed-variant: '#4b4263'
  tertiary-fixed: '#ffdf93'
  tertiary-fixed-dim: '#e7c365'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#594400'
  background: '#141218'
  on-background: '#e6e0e9'
  surface-variant: '#36343a'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  container-max: 1440px
---

## Brand & Style
The design system embodies the prestige of an elite global institute combined with the cutting-edge technicality of agentic AI. The aesthetic is **Cinematic Minimalism**—a high-contrast, dark-mode-first approach that uses deep forest greens to create a sense of infinite depth and biological growth.

The target audience consists of high-level researchers, engineers, and institutional stakeholders who value precision and authority. The UI should evoke a sense of "Living Intelligence"—stable and professional, yet punctuated by vibrant, organic transitions and luxury-grade gold accents. It borrows the structural rigour of high-end fintech and applies it to the frontier of AI training.

## Colors
The palette is rooted in the "Deep Forest" spectrum to provide a more sophisticated alternative to standard blacks. 

- **The Foundation:** The primary background is nearly black but retains a hint of organic chlorophyll. Surfaces are layered using slight tonal shifts rather than traditional shadows.
- **The Accents:** Gold is used sparingly for high-value interactions and critical branding. Emerald serves as the functional secondary, representing success, active states, and growth.
- **Living Grid:** A persistent decorative layer consists of a dot grid using `primary_gold` at 5% opacity, spaced at 28px intervals, providing a tactical, "blueprint" feel to the background.

## Typography
The typography strategy relies on extreme weight contrast. Headlines utilize the **Black (900)** and **Extra-bold (800)** weights of Inter to command attention and convey institutional power. 

Body text is strictly regulated to `slate-400` (#94a3b8) to ensure it recedes into the background, maintaining the cinematic focus on headers and key data points. Use `label-caps` for technical metadata and small navigation elements to reinforce the engineering-led nature of the platform.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop, centered within a wide 1440px container. It utilizes a 12-column system with generous 24px gutters to allow the deep background to "breathe" between content blocks.

**Animation as Layout:**
Spacing is not just static; it is temporal. 
- Elements should enter using the `entrance` (ease-out) curve with a 400ms duration.
- Background atmospheric elements (like the gold dot grid) may have subtle, slow-pulse `loop` animations over 8000ms+.
- Interactive elements like cards use the `spring` (interactive) token for a tactile, high-end feel.

## Elevation & Depth
In this design system, depth is achieved through **Tonal Layering** and **Subtle Illuminations** rather than heavy shadows.

- **Level 0 (Base):** #030a04 with the 5% gold dot grid.
- **Level 1 (Surface):** #071009 with a 1px border of #0d1f10.
- **Level 2 (Hover/Active):** A subtle inner glow of Emerald or Gold (2% opacity) to indicate focus.

Use backdrop blurs (20px+) for any modal overlays to maintain the "cinematic" feel, ensuring the underlying forest green tones bleed through.

## Shapes
The shape language is **Soft (0.25rem)**. This slight rounding provides a precision-engineered look that avoids the playfulness of more rounded systems. 

Buttons and input fields should strictly adhere to this radius. The only exception is the "Pill" shape used for status indicators (Chips) or secondary action triggers.

## Components

### Buttons
- **Primary:** Gradient fill (Emerald to Gold, 45-degree angle). Text is #030a04 (Deep Forest) for maximum legibility against the vibrant background.
- **Secondary:** Transparent background with a 1px Gold border. Text is Gold.
- **Ghost:** No background or border. Text is Slate-400, turning Gold on hover.

### Cards
- Surfaces use #071009.
- Borders are #0d1f10.
- On hover, the border transitions to Gold at 30% opacity, and the card scales slightly (1.02x) using the `interactive` spring token.

### Input Fields
- Background matches the surface (#071009).
- Bottom-border only or full subtle border depending on context. 
- Focus state: Border transitions to Emerald with a faint Emerald outer glow.

### Logo & Brand Marks
- Use a diagonal gradient from Emerald (#10b981) to Gold (#f59e0b).
- Any icon sets should use "Thin" or "Light" stroke weights to match the refined Inter typography.

### Chips/Badges
- Small, uppercase text. 
- Backgrounds are 10% opacity versions of the status color (Emerald for "Active", Gold for "Training").