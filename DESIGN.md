---
name: Velocity AI Sprint
colors:
  surface: '#faf9fd'
  surface-dim: '#dad9de'
  surface-bright: '#faf9fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f7'
  surface-container: '#eeedf2'
  surface-container-high: '#e8e7ec'
  surface-container-highest: '#e3e2e6'
  on-surface: '#1a1c1f'
  on-surface-variant: '#43474f'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f4'
  outline: '#747780'
  outline-variant: '#c3c6d0'
  surface-tint: '#405f8e'
  primary: '#001f41'
  on-primary: '#ffffff'
  primary-container: '#0f3460'
  on-primary-container: '#7f9dd0'
  inverse-primary: '#a9c8fc'
  secondary: '#835500'
  on-secondary: '#ffffff'
  secondary-container: '#feae2c'
  on-secondary-container: '#6b4500'
  tertiary: '#351700'
  on-tertiary: '#ffffff'
  tertiary-container: '#542800'
  on-tertiary-container: '#cf8e5c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a9c8fc'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#274774'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#ffb955'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb782'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#6b3a10'
  background: '#faf9fd'
  on-background: '#1a1c1f'
  surface-variant: '#e3e2e6'
typography:
  h1-desktop:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  h2-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  subheadline:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-main:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  button-text:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  gutter: 24px
  container-max: 1200px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The brand personality is professional, pragmatic, and highly efficient. It aims to evoke a sense of rapid progress and technical mastery while remaining accessible to business leaders. The design system leverages a **Modern Corporate** aesthetic with **Minimalist** and **Glassmorphic** influences.

Key attributes:
- **Trustworthy:** Deep blues and structured layouts signal reliability.
- **Dynamic:** High-contrast accents and subtle glowing gradients suggest the speed of a "sprint."
- **Clean:** Massive whitespace and purposeful typography ensure the AI technicality doesn't feel overwhelming.

## Colors
This design system utilizes a high-contrast palette to distinguish between high-energy "deep-work" zones and clean informational zones.

- **Primary Deep Blue:** Used for high-impact hero backgrounds, footer areas, and primary headings to establish authority.
- **Accent Orange/Yellow:** Reserved exclusively for Call-to-Action (CTA) elements and critical highlights to drive conversion.
- **Neutrals:** A combination of pure white and soft greys creates a layered effect for cards and secondary content sections.
- **Glow Effects:** Use a low-opacity version of the accent color or a cyan-blue tint for subtle radial gradients behind key visuals or icons in dark sections.

## Typography
The typography strategy prioritizes legibility and hierarchy. **Plus Jakarta Sans** provides a modern, slightly friendly geometric touch for headlines, while **Inter** ensures maximum readability for body content across all devices.

- **Headlines:** Use tight letter-spacing for large display text to create a compact, impactful look.
- **Body Text:** Maintain a generous line-height (1.6) to prevent fatigue during long-form reading.
- **Mobile scaling:** Scale headlines down aggressively for mobile while maintaining body text at a minimum of 16px for accessibility.

## Layout & Spacing
The layout follows a **Fixed Grid** model for the central content container, set at 1200px, with a 12-column structure. 

- **Whitespace:** Use significant vertical padding (120px+) between major sections to allow the design to "breathe" and signal a transition in the narrative.
- **Grid Alignment:** Elements like cards should span 4 columns (3-up) or 6 columns (2-up) for balanced information density.
- **Consistency:** Use an 8px base unit for all internal padding and margins to maintain a strict visual rhythm.

## Elevation & Depth
Depth is created through a mix of tonal layering and soft, modern shadows.

- **Tonal Layers:** In light mode, use `#F8F9FA` backgrounds to separate cards from the pure white `#FFFFFF` page surface.
- **Shadows:** Apply "Ambient Shadows"—highly diffused, low-opacity (8-12%) shadows with a slight blue tint (`#0F3460`). This makes elements like buttons and pricing cards appear to float naturally rather than being pasted on.
- **Dark Sections:** In deep blue areas, depth is achieved through glassmorphism (back-drop blur) and subtle inner strokes (1px, 10% white) to define the edges of containers.

## Shapes
The shape language is consistently rounded to soften the technical nature of AI.

- **Corner Radius:** A standard 8px (0.5rem) radius is applied to all buttons, input fields, and small cards. 
- **Large Containers:** For major feature sections or high-level containers, use `rounded-xl` (24px) to create a distinct, modern "app-like" feel.
- **Icons:** Use icons with rounded terminals and consistent stroke weights (1.5px or 2px) to match the typography.

## Components

- **Buttons:**
  - *Primary:* Accent Orange background, white or deep blue text, 8px corners, soft ambient shadow.
  - *Secondary:* Ghost style with a 1px border of Deep Blue or white (depending on background).
- **Cards:** White background with a 1px soft grey border. Use 16px-24px padding. In dark sections, use a semi-transparent Deep Blue with a subtle inner glow.
- **Input Fields:** 8px rounded corners, light grey background (`#F4F4F4`), 1px border that turns Deep Blue on focus.
- **Chips/Badges:** Small, pill-shaped labels with low-contrast backgrounds (e.g., light blue background with deep blue text) to denote categories or sprint days.
- **Progress Indicators:** Since this is a 14-day sprint, a horizontal timeline or stepped progress component is essential. Use the Accent color to show completion.
- **Feature Icons:** Housed in soft-rounded squares with a light tint of the primary color.