---
name: Apex Roofer SEO
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0d1c2f'
  on-tertiary-container: '#76859b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  h1:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  h2:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h3:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Work Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  stat-number:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '900'
    lineHeight: '1'
    letterSpacing: -0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  section-padding: 120px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style
This design system is engineered for a high-stakes, results-oriented service targeting the construction and roofing industry. The brand personality is authoritative, reliable, and "boots-on-the-ground" professional. It balances the grit of the roofing industry with the precision of data-driven digital marketing.

The aesthetic follows a **High-Contrast / Bold Minimalism** movement. It utilizes heavy whitespace to allow data visualizations to breathe, while employing aggressive, thick typography and high-energy accents to drive conversion. The goal is to evoke an immediate sense of "Emergency Growth"—positioning SEO not as a luxury, but as a critical infrastructure for the client's business.

## Colors
The palette is anchored by "Midnight Slate" (Primary), a deep blue-black that provides an unwavering foundation of trust and corporate stability. The primary canvas is "Arctic White," ensuring a sharp, clean environment for scannable content.

The accent color, "Emergency Orange," is reserved strictly for high-priority Call to Actions (CTAs) and critical data points. It creates a psychological sense of urgency and high visibility, mirroring the safety equipment found on a job site. Secondary slate tones are used for supporting UI elements and data visualization backgrounds to maintain a sophisticated, multi-layered appearance without sacrificing clarity.

## Typography
The typography system uses a dual-sans-serif approach to maximize both impact and readability. **Inter** is utilized for headlines and UI labels; its tight tracking and heavy weights command attention and project a modern, tech-forward image. 

**Work Sans** is selected for body copy and long-form content. Its slightly wider apertures and optimized legibility ensure that technical SEO explanations are easily digestible. A specialized `stat-number` style is defined for data visualization, emphasizing the scale of results (e.g., "300% ROI") with maximum visual weight.

## Layout & Spacing
The design system employs a **Fixed Grid** model for desktop, centered within a 1280px container to ensure readability and focus. A 12-column system provides the structure for data cards and service grids.

Generous vertical "Section Padding" (120px) is mandatory to create a premium, uncluttered feel. Elements are grouped using a tight 8px-base spacing scale, while separate content blocks utilize the "Stack-LG" (64px) unit to maintain a clear visual hierarchy. Mobile layouts transition to a single-column stack with 24px horizontal margins to maintain "thumb-friendly" interaction zones.

## Elevation & Depth
Depth is created through **Tonal Layers** and extremely subtle **Ambient Shadows**. Surfaces do not "float" in a traditional sense; instead, they sit on top of the neutral background with crisp, 1px borders in a slightly darker shade of the background color.

Shadows, when used on primary cards or CTAs, are "long and soft"—using a 15% opacity of the Primary Deep Blue color with a large blur radius (30px+) to suggest a gentle lift rather than a harsh drop. This keeps the interface feeling grounded and architectural. Data visualizations should appear "embedded" in the surface using subtle inner shadows or slightly darker background fills.

## Shapes
The shape language is "Soft" yet disciplined, favoring precision over playfulness. A 0.25rem (4px) base radius is applied to standard buttons and inputs to take the edge off the "industrial" feel without appearing bubbly. Large containers and feature cards use a `rounded-lg` (8px) radius. This conservative use of rounding maintains the professional, "engineered" aesthetic required for a trust-based B2B service.

## Components
- **Primary CTAs:** Solid "Emergency Orange" backgrounds with white, bold Inter text. These should use a 1px inset top-border of a lighter orange to create a subtle "pressed" or 3D effect without being skeuomorphic.
- **Data Cards:** Arctic White backgrounds with a 1px Slate-200 border. Use high-contrast bar charts or line graphs in Primary Blue.
- **Service Chips:** Small, uppercase labels with low-opacity Slate backgrounds and high-contrast text to categorize SEO services (e.g., "GMB OPTIMIZATION").
- **Input Fields:** Large, 56px height fields with a light gray fill and a focus state that utilizes a 2px Primary Blue border.
- **Trust Bar:** A full-width section with grayscale partner/certification logos, using a 50% opacity that returns to full color on hover.
- **Comparison Tables:** Clean rows with alternating light-gray fills (Zebra striping) to make data comparison scannable and undeniable.