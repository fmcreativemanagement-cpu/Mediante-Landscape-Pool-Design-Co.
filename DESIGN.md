---
name: Mediante Design System
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#44474c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#74777d'
  outline-variant: '#c4c6cc'
  surface-tint: '#506072'
  primary: '#041525'
  on-primary: '#ffffff'
  primary-container: '#1a2a3a'
  on-primary-container: '#8191a5'
  inverse-primary: '#b7c8dd'
  secondary: '#695d46'
  on-secondary: '#ffffff'
  secondary-container: '#efdec1'
  on-secondary-container: '#6d614a'
  tertiary: '#091425'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e293a'
  on-tertiary-container: '#8590a5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e4fa'
  primary-fixed-dim: '#b7c8dd'
  on-primary-fixed: '#0c1d2c'
  on-primary-fixed-variant: '#384859'
  secondary-fixed: '#f1e0c3'
  secondary-fixed-dim: '#d5c5a9'
  on-secondary-fixed: '#231a08'
  on-secondary-fixed-variant: '#504530'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
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
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  technical-data:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.5'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-padding: 120px
---

## Brand & Style
The design system embodies the intersection of architectural rigor and resort-level luxury. It is crafted for a high-end landscape and pool design studio that balances technical precision with an inviting, boutique aesthetic. The brand personality is authoritative yet tranquil, evoking the feeling of a private sanctuary.

The visual style is **Architectural Minimalism**. It prioritizes heavy whitespace to allow high-resolution project photography to breathe. Layouts are structured and disciplined, reflecting the "technically rigorous" nature of the studio, while rich color accents and high-contrast typography provide a "premium" editorial feel. The interface should feel like a physical portfolio: structured, tactile, and permanent.

## Colors
The palette is rooted in natural, architectural elements: stone, water, and earth.

- **Primary (Deep Navy):** Used for primary text, navigation backgrounds, and structural elements to provide a foundation of authority and depth.
- **Secondary (Sand Beige):** Used for subtle background sections, secondary buttons, and decorative borders to soften the technical navy.
- **Tertiary (Warm Slate):** Reserved for technical details, labels, and iconography where neutral clarity is required.
- **Accent (Muted Gold):** Reserved exclusively for high-impact calls to action and premium signifiers. It should be used sparingly to maintain its "prestige" status.
- **Neutral/Surface:** A palette of off-whites and very light grays to replace pure white in large areas, reducing eye strain and enhancing the "organic" feel.

## Typography
The typographic hierarchy creates a rhythm between editorial elegance and technical clarity.

- **Headlines:** Use Playfair Display for all major headings. It provides a classical, high-contrast serif look that communicates heritage and prestige. Use tighter letter-spacing for large display sizes to maintain a modern, "Vogue-like" aesthetic.
- **Body & Labels:** Use Inter for all functional text. Its neutral, systematic construction ensures that technical specifications and project details remain highly readable.
- **Styling Note:** Utilize the `label-caps` style for navigation items and small subtitles to inject an architectural, blueprint-inspired feel into the UI.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain a curated, gallery-like feel, while transitioning to a flexible fluid model on mobile.

- **Grid:** A 12-column grid with generous 32px gutters. Elements should often span 6 or 8 columns to create intentional "empty" space on either side, emphasizing the minimalist brand.
- **Rhythm:** Use an 8px base unit. Vertical spacing between sections should be expansive (120px+) to distinguish different project phases or services.
- **Safe Areas:** Maintain wide margins (64px) on desktop to prevent content from feeling crowded, reinforcing the "resort-grade" luxury of having "space to breathe."

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines** rather than aggressive shadows.

- **Surfaces:** Use the Sand Beige (#D4C4A8) at low opacities (5-10%) to create subtle "sun-bleached" surface containers that sit atop the primary Neutral background.
- **Outlines:** Use 1px solid borders in #D4C4A8 for cards and input fields. This creates a technical, architectural drawing look.
- **Shadows:** When necessary for interactivity (e.g., a hovered card), use a single, highly diffused "Ambient Shadow": `0 20px 40px rgba(26, 42, 58, 0.05)`. The shadow should be tinted with the Primary Navy to keep it integrated with the palette.
- **Imagery:** Use background blurs (10px - 20px) behind navigation bars to allow the texture of underlying project photography to peek through.

## Shapes
The shape language is **Soft (0.25rem)**. 

While the brand is architectural and rigorous, pure sharp corners (0px) can feel overly clinical or hostile. A subtle 4px radius on buttons and cards provides a "honed stone" effect—clean and precise, but refined and finished. 

- **Primary Buttons:** Should use the standard 4px radius.
- **Image Containers:** Use 4px radius to soften high-contrast landscape photography.
- **Decorative Elements:** Occasional use of "Pill" shapes is permitted for small category tags (Chips), but should be avoided for primary structural components.

## Components
- **Buttons:** 
  - *Primary:* Deep Navy background, White text, 4px radius, generous horizontal padding (32px).
  - *CTA:* Muted Gold background, Deep Navy text. Used only for "Book a Consultation."
  - *Ghost:* 1px border in Sand Beige, Primary Navy text.
- **Cards:** White background, 1px Sand Beige border, 4px radius. Content should have at least 32px internal padding.
- **Inputs:** Underlined or fully boxed with a 1px #D4C4A8 border. Labels must use the `label-caps` typography style positioned above the field.
- **Chips:** Small, Sand Beige background with Navy text, used for designating project types (e.g., "Infinity Pool," "Mediterranean Garden").
- **Lists:** Use a Muted Gold custom bullet point (small square or thin horizontal line) to maintain the architectural theme.
- **Project Gallery:** Full-width imagery with "Quick View" overlays using the Primary Navy at 90% opacity.