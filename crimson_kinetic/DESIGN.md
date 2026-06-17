---
name: Crimson Kinetic
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e7bdb6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ad8882'
  outline-variant: '#5d3f3b'
  surface-tint: '#ffb4a8'
  primary: '#ffb4a8'
  on-primary: '#690000'
  primary-container: '#be0000'
  on-primary-container: '#ffcac2'
  inverse-primary: '#c00301'
  secondary: '#ffb4ab'
  on-secondary: '#690006'
  secondary-container: '#d30017'
  on-secondary-container: '#ffe2de'
  tertiary: '#c8c6c5'
  on-tertiary: '#313030'
  tertiary-container: '#5e5d5d'
  on-tertiary-container: '#d9d6d6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#930000'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ab'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000c'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
  data-display:
    fontFamily: JetBrains Mono
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.0'
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
  margin-desktop: 64px
  margin-mobile: 20px
  container-max: 1440px
---

## Brand & Style

This design system is engineered for a premium, futuristic industrial portfolio. It targets high-stakes engineering firms and corporate recruiters by projecting an image of precision, analytical depth, and cinematic sophistication. The brand personality is "The Architect of Systems"—disciplined, forward-thinking, and uncompromising.

The aesthetic fuses **Corporate Minimalism** with **Cyber-Industrial** elements. It utilizes a dashboard-style layout characterized by modularity and data-driven visuals. The emotional response is one of immersion and trust; the UI feels like a high-end command center. Visual interest is generated through "tactile light"—subtle neon red glows that suggest energy flowing through a rigid, matte structural framework.

## Colors

The palette is anchored in a monochromatic spectrum of "Industrial Darks." The base is a true **Matte Black** to ensure infinite depth on OLED screens, layered with **Dark Graphite** and **Charcoal** for structural definition.

The signature element is the **Crimson Red** system. A deep, desaturated red is used for primary actions and semantic status, while a brighter "Neon Red" is reserved exclusively for luminous accents—such as hover states, active indicators, and glowing border effects. This contrast between the cold, heavy grays and the hot, energetic reds creates a cinematic tension that draws the eye to key project metrics and navigation points.

## Typography

The typography system prioritizes clarity and technical authority. **Inter** provides a clean, neutral foundation for all prose and headings, ensuring readability within dense dashboard layouts. 

To reinforce the industrial/engineering theme, **JetBrains Mono** is introduced for labels, metadata, and data visualizations. This monospaced secondary font acts as a "technical layer," signaling precision and automated processing. Headings should utilize tight letter-spacing to feel impactful and modern, while body text maintains generous leading to prevent visual fatigue in dark mode environments.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy to emulate a professional engineering dashboard. A 12-column system is used for desktop, with components snapping to a 4px baseline grid to ensure perfect alignment—a nod to blueprint precision.

Layout modules are separated by distinct "gutters of light"—thin lines or gaps that allow the background depth to show through. On mobile, the layout reflows into a single column, but maintains the "panelized" look by using inset containers with 20px safe margins. Padding within components should be generous (typically 24px or 32px) to provide the "premium" breathability expected in high-end portfolios.

## Elevation & Depth

Depth is created through **Tonal Layering** and **Subtle Glassmorphism** rather than traditional drop shadows.

1.  **Base Layer:** Matte Black (#0A0A0A) background.
2.  **Panel Layer:** Surface Graphite (#121212) with a 1px Charcoal border.
3.  **Floating Elements:** Use a backdrop-blur (12px) with a semi-transparent dark fill (80% opacity) to create a "glass" effect for navigation bars and modals.
4.  **Luminous Accents:** Active states and high-priority cards utilize a "Neon Glow"—a 1px inner border of Neon Red with a soft, diffused outer glow (blur: 8px, opacity: 0.15) to simulate hardware lighting.

## Shapes

The shape language is "Soft-Industrial." While 0px corners feel too aggressive and dated, high roundedness feels too consumer-friendly. 

This design system employs a consistent **0.25rem (4px) radius** for standard components (buttons, input fields, cards). This "Soft" setting maintains a disciplined, architectural feel while ensuring the UI feels modern and polished. Larger layout containers may scale up to 8px to define major sections, but the overall silhouette remains rectangular and grounded.

## Components

### Buttons
Primary buttons are solid Deep Crimson with white text. Secondary buttons are "Ghost" style: Charcoal borders that transition to a Neon Red border glow on hover. All buttons use the `label-mono` type style for a technical feel.

### Cards & Modules
The core of the dashboard aesthetic. Cards must have a 1px border (#262626). For featured projects, apply a subtle top-border gradient from Deep Crimson to Transparent.

### Inputs & Form Fields
Fields are dark-recessed (slightly darker than the panel layer) with a bottom-only border that illuminates in Neon Red when focused.

### Data Chips
Used for "Tools Used" or "Skills." These are small, monospaced capsules with a dark gray background and a 20% opacity Crimson text color, creating a "low-power" indicator look.

### Status Indicators
Small, circular "LED" dots. Use the Neon Red for "Active" or "Live" projects, with a subtle pulse animation to add life to the static portfolio.

### Dashboard Navigation
A vertical or horizontal bar with high backdrop-blur and a single 1px separating line. Active links are marked by a vertical red "power bar" indicator rather than a standard underline.