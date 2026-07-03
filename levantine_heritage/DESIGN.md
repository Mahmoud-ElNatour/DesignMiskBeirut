---
name: Levantine Heritage
colors:
  surface: '#f9f9fb'
  surface-dim: '#dadadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f5'
  surface-container: '#eeeeef'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#42474c'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f1f0f2'
  outline: '#72787d'
  outline-variant: '#c2c7cd'
  surface-tint: '#3e6379'
  primary: '#355970'
  on-primary: '#ffffff'
  primary-container: '#4e7289'
  on-primary-container: '#e5f3ff'
  inverse-primary: '#a6cbe5'
  secondary: '#9b4143'
  on-secondary: '#ffffff'
  secondary-container: '#fd8e8d'
  on-secondary-container: '#762528'
  tertiary: '#545657'
  on-tertiary: '#ffffff'
  tertiary-container: '#6c6e6f'
  on-tertiary-container: '#f1f1f2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6e7ff'
  primary-fixed-dim: '#a6cbe5'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#254b60'
  secondary-fixed: '#ffdad8'
  secondary-fixed-dim: '#ffb3b1'
  on-secondary-fixed: '#410007'
  on-secondary-fixed-variant: '#7d2a2d'
  tertiary-fixed: '#e2e2e3'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
  slate-blue: '#4E7289'
  brick-red: '#8F383A'
  marble-white: '#F5F5F6'
  onyx-text: '#1A1A1A'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  margin-desktop: 80px
  margin-mobile: 20px
  gutter: 24px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 48px
  section-gap: 120px
---

## Brand & Style

This design system embodies the high-luxury hospitality of Misk Beirut, merging Mediterranean warmth with editorial precision. The aesthetic is rooted in **Minimalism** with a **Corporate/Modern** structural foundation, prioritizing expansive whitespace and sophisticated "asymmetric balance."

The brand personality is cultured, epicurean, and timeless. It aims to evoke the feeling of a sun-drenched Levantine afternoon—refined but deeply welcoming. The UI avoids trendy visual clutter, instead relying on the tension between classical serif typography and a rigorous, modern grid. High-quality photography of food and architecture serves as the primary visual driver, framed by generous margins and subtle, masonry-inspired layouts.

## Colors

The palette is inspired by the natural materials and landscapes of the Mediterranean coast. 

- **Slate Blue (#4E7289):** Used for primary actions, subtle iconography, and structural accents. It represents the sea and sky, providing a calm, professional anchor.
- **Brick Red (#8F383A):** Reserved for highlights, special call-outs (like "Book a Table"), and active states. It draws from traditional terracotta and spices.
- **Marble White (#F5F5F6):** The primary background color. It is softer than pure white, reducing eye strain and adding a sense of physical materiality.
- **Onyx Text (#1A1A1A):** A near-black used for body text to ensure maximum legibility while maintaining a softer edge than true black.

## Typography

The typography strategy relies on the contrast between the intellectual, historical character of **EB Garamond** and the clean, functional efficiency of **Hanken Grotesk**.

- **Headlines:** Use EB Garamond for all editorial titles, storytelling blocks, and menu categories. Headlines should feel "set" like a premium magazine.
- **Body:** Use Hanken Grotesk for all descriptive text, ingredient lists, and functional information. It ensures clarity at smaller scales.
- **Labels:** Small labels and navigation items should be set in Hanken Grotesk with increased letter-spacing and uppercase styling to create a modern, architectural feel.

## Layout & Spacing

This design system utilizes a **Fixed Grid** for desktop (1280px max-width) and a **Fluid Grid** for mobile. 

- **The Editorial Grid:** On desktop, use a 12-column grid. Components should frequently "break" the expected symmetry—for example, a large image spanning 7 columns with text occupying only 4 columns of the opposite side, leaving an empty column in between.
- **Vertical Rhythm:** Sections are separated by large gaps (120px+) to allow the content to breathe. Use "Stack" units for internal component spacing.
- **Responsive Behavior:** On mobile, margins shrink to 20px, and multi-column editorial layouts collapse into a single vertical stack. Hero images should maintain a fixed aspect ratio (3:4 or 4:5) to preserve the editorial feel.

## Elevation & Depth

The design system avoids heavy shadows, instead using **Tonal Layers** and **Low-Contrast Outlines** to communicate hierarchy.

- **Surfaces:** Depth is created by placing white cards on top of the Marble White background. Use a very subtle, diffused shadow (0px 4px 20px rgba(0,0,0, 0.04)) only for floating elements like navigation bars or primary modals.
- **Layering:** Overlap images and text blocks slightly to create a sense of physical collage. 
- **Dividers:** Use thin (1px) lines in Slate Blue at 10% opacity to separate sections without creating visual "walls."

## Shapes

The shape language is primarily **Soft (0.25rem)**. 

While the layout is overall very geometric and structured, slight rounding on buttons and card containers prevents the UI from feeling overly clinical or sharp. Larger elements like hero images should remain perfectly sharp (0px) to mimic high-end photography prints, while interactive elements like buttons and input fields use the soft radius for tactile comfort.

## Components

- **Buttons:** Primary buttons use a solid Slate Blue fill with white Hanken Grotesk labels in uppercase. Secondary buttons use a Slate Blue 1px outline with no fill.
- **Cards:** Cards for menu items or blog posts should be borderless with a clean Marble White background and generous internal padding (32px).
- **Input Fields:** Use a simple bottom-border only (1px Slate Blue) for a minimalist, "registration desk" aesthetic. Labels should float above the line.
- **Chips/Tags:** Used for dietary requirements or location tags. Small, uppercase, with a 0.25rem radius and a light Slate Blue tint.
- **Lists:** Menu lists should follow an editorial format: Item Name (Garamond), a dotted leader or simple space, followed by Price, with the Description (Hanken) underneath in a lighter gray.
- **Navigation:** A centered, minimalist top bar. On scroll, it should transition to a frosted glass effect (backdrop-filter: blur) with a thin bottom border.