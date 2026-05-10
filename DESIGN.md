---
name: World Unfold
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
  on-surface-variant: '#414844'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#717973'
  outline-variant: '#c1c8c2'
  surface-tint: '#3f6653'
  primary: '#012d1d'
  on-primary: '#ffffff'
  primary-container: '#1b4332'
  on-primary-container: '#86af99'
  inverse-primary: '#a5d0b9'
  secondary: '#006399'
  on-secondary: '#ffffff'
  secondary-container: '#67bafd'
  on-secondary-container: '#004972'
  tertiary: '#012b31'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c4147'
  on-tertiary-container: '#88acb4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c1ecd4'
  primary-fixed-dim: '#a5d0b9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#274e3d'
  secondary-fixed: '#cde5ff'
  secondary-fixed-dim: '#94ccff'
  on-secondary-fixed: '#001d32'
  on-secondary-fixed-variant: '#004b74'
  tertiary-fixed: '#c3e9f1'
  tertiary-fixed-dim: '#a8cdd5'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#284c53'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is rooted in the concept of "Discovery through Clarity." It moves away from the chaotic primary colors and cluttered interfaces typical of children's software, instead opting for a sophisticated, **Modern-Organic** aesthetic. This approach treats children as capable, curious explorers, providing them with a high-quality environment that inspires awe and respect for the natural world.

The emotional response should be one of "calm wonder." By utilizing generous whitespace and a tactile, layered interface, the design system facilitates deep focus and academic exploration. It blends the precision of **Corporate Modernism** with the warmth of **Minimalist Naturalism**, ensuring the platform feels like a prestigious digital encyclopedia rather than a toy.

## Colors

The palette is derived from the stratification of the natural world. 
- **Land (Primary):** Deep Forest Green serves as the foundation for primary actions and authoritative headers, providing a grounded, stable feeling.
- **Ocean (Secondary):** Rich Ocean Blues are used for interactive elements, links, and progress indicators, representing depth and fluidity.
- **Sky (Tertiary):** Airy Light Blues and near-white Sky tones provide the background canvas and soft highlights, ensuring the UI remains breathable and expansive.

Backgrounds should primarily use the "Sky" spectrum to maintain a high-key, optimistic atmosphere, while "Land" tones are reserved for moments of high importance or content finality.

## Typography

The design system utilizes **Plus Jakarta Sans** as the primary typeface. Its soft, modern curves provide the "friendly" quality required for a younger audience, while its geometric precision maintains an "authoritative" educational tone. 

For technical data, metadata, and UI labels, **Work Sans** is used to provide a grounded, professional contrast. This pairing ensures that while the narrative content feels inviting, the functional aspects of the platform feel reliable and precise. Large display sizes should use tighter letter spacing to maintain a cohesive, editorial look.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. On desktop, content is housed within a 1280px max-width container to prevent line lengths from becoming unreadable, while backgrounds and immersive "World" elements bleed to the edges.

A 12-column grid is used for desktop (24px gutters), transitioning to a 4-column grid for mobile (16px gutters). Spacing follows a strictly enforced 8px rhythm. Large "Sky" gaps (48px to 80px) are used between major content sections to prevent cognitive overload, mirroring the openness of a natural landscape.

## Elevation & Depth

To maintain a modern and professional feel, this design system avoids heavy shadows in favor of **Tonal Layering** and **Soft Ambient Occlusion**.

1.  **Surface Tiers:** The base "Sky" layer is the lowest. Cards and content containers sit on top using white backgrounds with extremely subtle, 1px borders in a light "Ocean" tint.
2.  **Depth:** Instead of traditional shadows, use "Soft Depths"—very large blur radii (30px+) with very low opacity (4-6%) using the primary "Land" or "Ocean" color as the shadow tint. This makes elements feel like they are floating gently rather than sitting on a harsh surface.
3.  **Active States:** Interactive elements may use a slight inner shadow when pressed to mimic tactile feedback without looking "childish."

## Shapes

The shape language is defined by "Natural Geometry." While elements are structured and professional, they avoid sharp, aggressive corners. A **Level 2 (Rounded)** approach is the standard. 

- **Cards and Modals:** 1rem (16px) corner radius to feel approachable.
- **Buttons and Chips:** 0.5rem (8px) for a more precise, functional appearance.
- **Imagery:** Large feature images should utilize 1.5rem (24px) radii or organic, non-perfect circular masks to mimic natural forms like pebbles or leaves.

## Components

- **Buttons:** Primary buttons use the "Land" green with white text. They should have a subtle "lift" on hover. Secondary buttons use "Ocean" outlines.
- **Progress Trackers:** Designed as "Paths." Use thick, rounded lines in light blue that fill with deep "Ocean" blue as the child progresses.
- **Cards:** Content cards should be clean with high-quality photography as the focus. Typography is placed on the white area below the image, never overlaid, to ensure maximum readability.
- **Input Fields:** Use a light "Sky" background with a 1px "Ocean" border that thickens slightly on focus. Avoid floating labels; use clear, authoritative "Work Sans" labels above the field.
- **Discovery Chips:** Small, pill-shaped tags used for categories (e.g., "Biology," "Space"). These use desaturated versions of the natural palette to avoid looking like "candy."
- **Interactive Maps:** A custom component for this design system, using a simplified topographic style with the "Land" and "Ocean" palette to guide navigation through learning modules.