---
name: Togo Excellence Portal
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#47464b'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#78767b'
  outline-variant: '#c8c5cb'
  surface-tint: '#5f5e62'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1f'
  on-primary-container: '#848388'
  inverse-primary: '#c8c5cb'
  secondary: '#0054cb'
  on-secondary: '#ffffff'
  secondary-container: '#316ee8'
  on-secondary-container: '#fefcff'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e1e7'
  primary-fixed-dim: '#c8c5cb'
  on-primary-fixed: '#1b1b1f'
  on-primary-fixed-variant: '#47464b'
  secondary-fixed: '#dae2ff'
  secondary-fixed-dim: '#b1c5ff'
  on-secondary-fixed: '#001847'
  on-secondary-fixed-variant: '#0040a0'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  title-md:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
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
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

This design system establishes a digital gateway that balances the prestigious efficiency of modern municipal governance with the rich cultural heritage of Togo. Inspired by the architectural and digital sophistication of Dubai, the visual language is defined by **High-End Minimalism** and **Glassmorphism**.

The system aims to evoke a sense of "Futuristic Trust"—where citizens feel they are interacting with a world-class, forward-thinking institution. Key characteristics include:
- **Luminous Transparency:** Using frosted glass effects to create depth without clutter.
- **Organic Precision:** Combining strict geometric layouts with generous, soft rounded corners to feel approachable yet organized.
- **National Pride:** Subtle infusion of Gold and Emerald Green accents into a sterile, premium foundation of whites and deep blues.
- **Clarity of Motion:** Micro-interactions that respond to user intent with fluid, frictionless ease.

## Colors

The palette is anchored in **Deep Midnight Blue (#1B1B1F)** for primary navigation and text to ensure authority and readability. **Pure White (#FFFFFF)** and **Pearl Gray (#FAFAFA)** form the expansive background canvas, allowing for a high-contrast, airy feel.

To reflect Togo’s municipal identity, two specific accents are utilized:
- **Municipal Gold (#D4AF37):** Used sparingly for high-value CTAs, achievement badges, and premium iconography.
- **Heritage Emerald (#006A4E):** Used for success states, environmental initiatives, and secondary interactive elements.

Glassmorphic elements utilize a semi-transparent white base with a 20px-40px backdrop blur to maintain legibility over photography.

## Typography

The typography system prioritizes extreme legibility and a systematic hierarchy. **Montserrat** is the display face, chosen for its geometric perfection and modern municipal feel. **Inter** handles all functional and body text, providing a neutral, highly readable experience at all scales.

Generous line-heights are maintained (1.5x minimum for body text) to support the minimalist aesthetic and reduce cognitive load. Titles should use tight letter spacing to appear "locked" and authoritative, while labels use expanded letter spacing for better scanning at small sizes.

## Layout & Spacing

The layout follows a **12-column fixed grid** on desktop, centering content with wide outer margins to maintain a premium "editorial" feel. 

- **Desktop (1440px+):** 12 columns, 24px gutters, 80px side margins.
- **Tablet (768px - 1439px):** 8 columns, 16px gutters, 40px side margins.
- **Mobile (Up to 767px):** 4 columns, 16px gutters, 20px side margins.

Vertical spacing follows an 8px base unit. Section-to-section spacing should be aggressive (typically 120px to 160px) to reinforce the high-end minimalist theme and allow the glassmorphic components to "breathe."

## Elevation & Depth

Depth is conveyed through **Glassmorphism** rather than traditional heavy shadows.
- **Base Level:** Solid Pearl Gray (#FAFAFA) or high-quality landscape photography.
- **Elevated Level (Cards/Modals):** A semi-transparent surface (rgba 255, 255, 255, 0.7) with a `backdrop-filter: blur(20px)`. 
- **Borders:** Instead of shadows, use a 1px solid white border with 20% opacity to define the edges of glass containers, simulating a light-catching "glass edge."
- **Interaction Depth:** On hover, elements should slightly scale (1.02x) and increase the backdrop blur intensity rather than adding a dark shadow.

## Shapes

The shape language is defined by large, elegant radii. **Standard elements** (buttons, inputs) utilize a 0.5rem (8px) radius. **Container elements** (cards, hero sections) utilize a much larger `rounded-xl` (24px) or even 32px radius to create a soft, futuristic aesthetic.

Search bars and primary action buttons may adopt a "Pill" shape (fully rounded sides) to distinguish them as high-priority interactive touchpoints.

## Components

### Buttons
Primary buttons use a Deep Midnight Blue background with white text. Secondary buttons are "Ghost" style with a 1px Midnight Blue border. Floating Action Buttons (FABs) or special highlights use a Gold gradient. All buttons feature a 0.3s cubic-bezier transition on hover.

### Glassmorphic Cards
Used for municipal services. Features a white translucent background, a 24px corner radius, and the thin "light-catch" border. Icons within cards should be "duotone" using Midnight Blue and Gold.

### Sleek Search Bar
A prominent, oversized pill-shaped input. It should feature a subtle inner shadow and a glassmorphic background when placed over imagery. The magnifying glass icon is Gold.

### Refined Iconography
Icons must be thin-stroke (1.5pt), geometric, and consistent. Avoid filled icons unless indicating an active state.

### Elegant Sliders
Used for budget transparency or service selection. The track is Pearl Gray, and the handle is a large, Gold-bordered white circle that expands slightly when dragged.

### Animations
- **Scroll Reveals:** Sections should fade and slide up 20px as they enter the viewport.
- **Glass Transitions:** When a modal opens, the background should blur progressively over 0.5s.