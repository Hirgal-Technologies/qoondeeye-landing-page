---
name: Qoondeeye Fintech System
colors:
  surface: '#f8fafb'
  surface-dim: '#d8dadb'
  surface-bright: '#f8fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f5'
  surface-container: '#eceeef'
  surface-container-high: '#e6e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#40484c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#eff1f2'
  outline: '#71787d'
  outline-variant: '#c0c7cd'
  surface-tint: '#2a657e'
  primary: '#003345'
  on-primary: '#ffffff'
  primary-container: '#004b63'
  on-primary-container: '#83bad6'
  inverse-primary: '#96ceeb'
  secondary: '#50606f'
  on-secondary: '#ffffff'
  secondary-container: '#d1e1f4'
  on-secondary-container: '#556474'
  tertiary: '#273033'
  on-tertiary: '#ffffff'
  tertiary-container: '#3d464a'
  on-tertiary-container: '#abb4b8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bfe8ff'
  primary-fixed-dim: '#96ceeb'
  on-primary-fixed: '#001f2b'
  on-primary-fixed-variant: '#044d65'
  secondary-fixed: '#d4e4f6'
  secondary-fixed-dim: '#b8c8da'
  on-secondary-fixed: '#0d1d2a'
  on-secondary-fixed-variant: '#394857'
  tertiary-fixed: '#dbe4e8'
  tertiary-fixed-dim: '#bfc8cc'
  on-tertiary-fixed: '#141d20'
  on-tertiary-fixed-variant: '#3f484b'
  background: '#f8fafb'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 68px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style
The design system is built on the principles of **Modern Trust and Financial Clarity**. It targets Somali individuals and families seeking a professional, reliable tool for personal finance management. The aesthetic moves away from aggressive "disruptive" fintech visuals, opting instead for a **Sophisticated Corporate-Modern** style that emphasizes stability and accessibility.

The emotional response should be one of "controlled growth"—the UI feels expansive due to heavy whitespace but remains grounded through a deep, authoritative primary palette. We utilize a mix of Minimalism for layout and subtle Glassmorphism for depth, ensuring the product feels premium yet approachable.

## Colors
The color strategy prioritizes legibility and calm.
- **Primary (#004B63):** A deep, oceanic blue used for key branding, primary actions, and navigational anchors. It represents the "Trust" pillar of the brand.
- **Secondary (#708090):** A soft slate gray used for secondary text and supporting icons, reducing visual noise.
- **Surface & Background:** Extensive use of pure white (#FFFFFF) for main containers and Neutral (#F8FAFB) for page sections to create a clean, editorial feel.
- **Accents:** Tertiary blue-whites are used for subtle background washes and card fills to prevent the design from feeling "stark."

## Typography
The system uses **Manrope** exclusively to maintain a modern, geometric, yet highly readable appearance. 
- **Editorial Hierarchy:** Headlines use tighter letter-spacing and heavier weights (Bold/ExtraBold) to command attention. 
- **Body Text:** Ample line height (1.5x - 1.6x) is applied to ensure financial data and descriptive copy are easy to digest.
- **Contextual Scaling:** For mobile, display sizes are aggressively reduced while maintaining the negative letter-spacing to preserve the "premium" character of the brand.

## Layout & Spacing
This design system utilizes a **12-column fixed grid** for desktop and a **4-column fluid grid** for mobile. 
- **The "Breathe" Principle:** We employ generous section gaps (120px) to separate brand stories and product features, reinforcing the minimalist aesthetic.
- **Grid Alignment:** All card-based components should align to the grid gutters.
- **Safe Margins:** On mobile, a 20px horizontal margin is mandatory. On desktop, the layout is centered with a max-width of 1280px.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows** rather than harsh borders.
- **Shadows:** Use a "Natural Ambient" shadow style: `0px 10px 30px rgba(0, 75, 99, 0.05)`. The shadow color is tinted with the primary blue to maintain color harmony.
- **Gradients:** Subtle linear gradients (e.g., `#FFFFFF` to `#F8FAFB`) are used on large background sections to provide a soft sense of curvature and light.
- **Glassmorphism:** Navigation bars use a backdrop blur (20px) with a semi-transparent white fill (80% opacity) to stay visible over dynamic content.

## Shapes
The shape language is consistently **Rounded**. 
- **Cards & Mockups:** Use a base radius of 16px (`rounded-lg`) or 24px (`rounded-xl`) to evoke a friendly, modern tech feel.
- **Interactive Elements:** Buttons and input fields follow the `rounded-lg` (16px) standard to match the mockups.
- **Iconography:** Icons should feature rounded caps and corners, avoiding sharp points to remain consistent with the container language.

## Components
- **Primary Buttons:** Solid `#004B63` fill with white text. High padding (16px top/bottom, 32px left/right). 16px border-radius.
- **App Store CTAs:** "Get it on Google Play" buttons should use a secondary-themed dark border or solid neutral-dark background, featuring the official brand assets.
- **Feature Cards:** White background, 1px subtle border in `#E8F1F5`, and the "Natural Ambient" shadow. Content inside should be left-aligned with a 32px internal padding.
- **Phone Mockups:** High-fidelity, bezel-less device frames. Content inside the mockups should mirror the app's clean UI, using the same primary blue and slate gray palette.
- **Input Fields:** Soft gray background (#F8FAFB) with no border until focused. On focus, a 1.5px border of the Primary Blue appears.
- **Line Icons:** 2px stroke width, using the Primary or Secondary colors. Always enclosed in a soft-colored circular or squircle container.