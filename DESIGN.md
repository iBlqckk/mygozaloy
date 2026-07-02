---
name: Gozaloy's Moon
colors:
  surface: '#fefccf'
  surface-dim: '#dedcb1'
  surface-bright: '#fefccf'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f6c9'
  surface-container: '#f2f0c4'
  surface-container-high: '#eceabe'
  surface-container-highest: '#e6e5b9'
  on-surface: '#1d1d03'
  on-surface-variant: '#4d4732'
  inverse-surface: '#323214'
  inverse-on-surface: '#f5f3c7'
  outline: '#7e775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#e9c400'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#ffbf00'
  on-secondary-container: '#6d5000'
  tertiary: '#874e58'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffcdd4'
  on-tertiary-container: '#874e58'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#fbbc00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#fcb3be'
  on-tertiary-fixed: '#360c17'
  on-tertiary-fixed-variant: '#6b3741'
  background: '#fefccf'
  on-background: '#1d1d03'
  surface-variant: '#e6e5b9'
typography:
  display-lg:
    fontFamily: comfortaa
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: comfortaa
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: comfortaa
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md-mobile:
    fontFamily: comfortaa
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  title-lg:
    fontFamily: comfortaa
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.6'
  label-md:
    fontFamily: quicksand
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 8px
  container-margin: 24px
  gutter: 16px
  section-gap-lg: 80px
  section-gap-sm: 40px
---

## Brand & Style

The design system is built upon the concept of "luminous warmth." It targets an audience seeking a personal, intimate connection, evoking the feeling of a sun-drenched afternoon or a soft moonlight glow. The personality is unapologetically affectionate, whimsical, and gentle.

The visual style departs from rigid corporate structures in favor of **Soft-Toasted Minimalism**. It utilizes exaggerated roundedness, organic layering, and a "glow" effect to create a sense of tactile comfort. Every interaction should feel like a soft gesture rather than a mechanical input.

## Colors

The palette is a harmonic blend of celestial warmth and floral pastels. 
- **Primary & Secondary:** These golden and amber tones represent the "Moon" and "Glow," used for call-to-action elements and highlights.
- **Tertiary & Quaternary:** Soft Pink and Pastel Lavender provide a romantic, whimsical contrast, perfect for decorative accents, chips, and secondary status indicators.
- **Neutral & Background:** A warm white (`#FFFEF2`) and soft cream (`#FFFDD0`) form the foundation, ensuring the UI feels cozy rather than clinical.

Avoid pure blacks; use a deep, warm grey or a desaturated amber for text to maintain the soft aesthetic.

## Typography

This design system uses a dual-rounded typography strategy. **Comfortaa** provides a playful, geometric, and almost handwritten personality for all headers and display text. Its wide apertures and soft curves reinforce the "affectionate" brand voice.

**Quicksand** is used for body text and labels to maintain legibility while echoing the rounded shapes of the headings. Line heights are generous to prevent the UI from feeling cramped, ensuring a breezy and relaxed reading experience. Use `body-lg` for primary storytelling and `label-md` in uppercase for small organizational elements.

## Layout & Spacing

The layout philosophy follows a **Breathable Fluidity** model. Instead of rigid containers, the system uses large margins and "safe zones" to let content float naturally. 

- **Grid:** A 12-column fluid grid on desktop, transitioning to a 4-column grid on mobile. 
- **Rhythm:** Spacing is based on an 8px base unit, but preference is given to larger gaps (`section-gap-lg`) to maintain a sense of calm and prevent visual clutter.
- **Adaptive Behavior:** On mobile, margins reduce from 24px to 16px, and vertical spacing is tightened slightly to accommodate smaller viewports while preserving the "airy" feel.

## Elevation & Depth

To achieve a "cozy" feeling, the design system avoids harsh, high-contrast shadows. Instead, it employs **Luminous Ambient Depth**:

1.  **Low-Opacity Tints:** Shadows are never pure grey; they are tinted with the primary amber or secondary pink colors (e.g., a shadow with a 5% opacity of `#FFBF00`).
2.  **Diffuse Blurs:** Shadows have large blur radii and zero spread, making elements appear as if they are resting on a soft cushion.
3.  **Tonal Stacking:** Surfaces use subtle shifts in background color (e.g., moving from the warm white background to a Soft Cream card) to indicate hierarchy without needing heavy borders.

## Shapes

The shape language is strictly **Ultra-Rounded**. There are no sharp corners in this design system. 

- **Primary Radius:** Set to Level 3 (Pill-shaped). Buttons, tags, and small containers should always use fully rounded ends.
- **Card Radius:** Larger containers use `rounded-xl` (3rem) to create a "bubbly" and inviting frame for content.
- **Decorative Elements:** Use heart-shaped icons or circular "blobs" as background accents. Image masks should ideally use organic, non-uniform rounded shapes or soft circles.

## Components

- **Buttons:** Use a "squishy" appearance. High-priority buttons should be Amber (#FFBF00) with a Soft Pink shadow. Hover states should slightly increase the shadow blur and scale the button by 2% for a tactile response.
- **Cards:** White or Cream background with a `rounded-xl` corner. Use a soft Lavender or Pink border (1px, 20% opacity) instead of a dark outline.
- **Input Fields:** Fully rounded (pill) containers with a Soft Cream fill. Focus states should trigger a Soft Golden glow around the perimeter.
- **Chips & Tags:** Use the Secondary Pink and Lavender colors with white text. These should always be pill-shaped.
- **Icons:** Use "duotone" or "rounded" icon sets. Incorporate heart-shaped accents for favorites, likes, or decorative dividers between sections.
- **Floating Action Button (FAB):** A signature Golden Yellow circle with a white heart icon, used for the primary point of engagement (e.g., "Send a Message").