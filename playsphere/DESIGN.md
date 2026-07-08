---
name: PlaySphere Kinetic
colors:
  surface: '#fff8f6'
  surface-dim: '#f0d4ce'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ed'
  surface-container: '#ffe9e5'
  surface-container-high: '#ffe2dc'
  surface-container-highest: '#f9dcd6'
  on-surface: '#271814'
  on-surface-variant: '#434655'
  inverse-surface: '#3e2c28'
  inverse-on-surface: '#ffede9'
  outline: '#8f7069'
  outline-variant: '#e3beb6'
  surface-tint: '#b52603'
  primary: '#b52603'
  on-primary: '#ffffff'
  primary-container: '#ff5a36'
  on-primary-container: '#5a0c00'
  inverse-primary: '#ffb4a3'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#6df5e1'
  on-secondary-container: '#006f64'
  tertiary: '#4858ab'
  on-tertiary: '#ffffff'
  tertiary-container: '#7d8ce4'
  on-tertiary-container: '#0d2075'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a3'
  on-primary-fixed: '#3d0600'
  on-primary-fixed-variant: '#8c1900'
  secondary-fixed: '#70f8e4'
  secondary-fixed-dim: '#4fdbc8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005048'
  tertiary-fixed: '#dee0ff'
  tertiary-fixed-dim: '#bac3ff'
  on-tertiary-fixed: '#00105b'
  on-tertiary-fixed-variant: '#2f3f92'
  background: '#fff8f6'
  on-background: '#271814'
  surface-variant: '#f9dcd6'
  clay-bg: '#F5EFE9'
  primary-soft: '#FF8A70'
  surface-card: '#FFFFFF'
  map-teal: '#00B4A2'
typography:
  display-hero:
    fontFamily: Nunito
    fontSize: 80px
    fontWeight: '900'
    lineHeight: '1.05'
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Nunito
    fontSize: 56px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-section:
    fontFamily: Nunito
    fontSize: 48px
    fontWeight: '900'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Nunito
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Nunito
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.6'
  body-md:
    fontFamily: Nunito
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.5'
  button:
    fontFamily: Nunito
    fontSize: 18px
    fontWeight: '700'
    lineHeight: '1'
  label-caps:
    fontFamily: Nunito
    fontSize: 14px
    fontWeight: '800'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  xs: 4px
  base: 8px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  container-max: 1280px
---

## Brand & Style

PlaySphere Kinetic is a vibrant, community-centric design system for the "Your City is Your Playground" ecosystem. The brand personality is **energetic, welcoming, and tactile**, targeting active urban dwellers and sports enthusiasts. 

The visual style is **Soft-Tactile (Claymorphism-Lite)**. It blends organic, high-roundedness shapes with deep, ambient shadows and subtle internal gradients to create a "squishy," physical feel that mimics sports equipment and outdoor surfaces. The use of vibrant accent colors against a warm, earthy "Soft Clay" background evokes a sunset-on-the-court feeling, balancing high-energy action with approachable community vibes.

Key visual signatures include:
- **Floating Geometry:** Elements appear to hover at various altitudes using soft-deep shadows.
- **Organic Accents:** Underlines and background blobs are irregular and fluid, suggesting movement.
- **Glass-Tactile Mix:** Frosted glass navigation bars paired with "clay" buttons that have inner-light highlights.

## Colors

The palette is anchored by **Sunset Orange (#FF5A36)**, a high-visibility primary color that represents energy and competition. This is balanced by a **Soft Clay (#F5EFE9)** background, which provides a warmer, more premium alternative to standard white or grey, mimicking natural outdoor environments.

**Secondary Accents:**
- **Teal (#00B4A2):** Used for "Live" states, availability, and growth-oriented actions.
- **Indigo (#5C6BC0):** Used for community, tournaments, and institutional information.

**Functional Application:**
- Surfaces are primarily pure white to maintain legibility against the clay background.
- Background "Blobs" use low-opacity versions (15-20%) of the primary and secondary colors to create a sense of depth and atmospheric perspective.

## Typography

The system exclusively utilizes **Nunito**, chosen for its rounded terminals which perfectly complement the claymorphic shape language. 

**Hierarchical Strategy:**
- **Heavy Weighting:** Headlines use Black (900) or ExtraBold (800) weights to dominate the visual field and convey confidence.
- **Tighter Tracking:** Display and hero styles utilize negative letter-spacing (-0.03em) to keep large text blocks feeling cohesive and "graphic."
- **Optimized Legibility:** Body text stays at a minimum of 18px and a Medium/SemiBold weight to ensure readability against colorful, textured backgrounds. 
- **Thematic Labels:** Small labels use heavy tracking and uppercase styling to denote metadata or "Live" status indicators.

## Layout & Spacing

PlaySphere Kinetic uses a **Fixed Grid with Fluid Padding** model. The central content container is capped at 1280px for desktop layouts to prevent excessive line lengths in the hero section.

**Spacing Rhythm:**
- A base unit of **8px** is used for internal component spacing.
- Large **80px (xl)** vertical gaps are used between major sections to maintain the "airy" and expansive feeling of a playground.
- **32px to 48px** margins are standard for mobile/tablet breakpoints to ensure content doesn't hit the screen edges.

**Grid Behavior:**
- 12-column grid for desktop.
- 6-column grid for tablet.
- 4-column grid for mobile.
- Section titles are typically centered to emphasize the "Community Hub" focus.

## Elevation & Depth

Elevation is the primary driver of the system's "tactile" feel. We avoid flat surfaces in favor of multi-layered depth.

- **Level 1 (Sub-surface):** Background blobs and gradients that sit behind the main content container.
- **Level 2 (Ground):** The main "Soft Clay" page background.
- **Level 3 (Floating):** Standard cards and navigation bars. These use "Soft Deep" shadows (0 20px 40px) that give the impression of an object floating 20-30 pixels above the ground.
- **Level 4 (Active/Interaction):** Map markers and high-priority action items. These utilize CSS animations (bounce) and even deeper shadows to demand immediate attention.
- **Internal Depth:** "Clay" buttons use a distinctive **inset white shadow** (top-down) to simulate a 3D-molded plastic or rubber button.

## Shapes

The shape language is **exuberantly rounded**. Sharp corners are strictly avoided to maintain the friendly, approachable "Play" theme.

- **Cards:** Use a `2rem` (32px) radius for a soft, friendly container.
- **Primary Actions:** Always use `9999px` (Full Pill) radius for buttons and search inputs.
- **Section Transitions:** The footer and header utilize top-heavy or bottom-heavy rounding (`3rem` or 48px) to "envelope" the content, making the page feel like a single cohesive object rather than a series of flat slices.

## Components

### Buttons
- **Clay Button (Primary):** Sunset Orange background, full-pill radius, white text. Features an inset white highlight on the top edge and a color-tinted drop shadow (`rgba(255, 90, 54, 0.3)`).
- **Soft Button (Secondary):** Pure white background with a soft-deep shadow. Transitions to a subtle scale-up on hover.

### Cards
- **Soft Cards:** White background, 2rem roundedness. On hover, cards should translate -8px vertically and scale by 1.02, with the shadow softening further to simulate "rising" toward the user.
- **Story Cards:** Feature a background image or color with a bottom-up black gradient overlay (80% opacity) to ensure white typography remains legible.

### Navigation
- **Floating Pill Nav:** The desktop nav utilizes a white, semi-opaque background (`bg-white/80`) with a `backdrop-blur-xl` effect and a pill-shaped container to distinguish the internal links from the overall page header.

### Map Elements
- **Markers:** 2rem rounded containers with high-contrast icons. Markers should utilize a persistent "float" or "bounce" animation to indicate interactivity.
- **Perspective Containers:** Use a `20deg` X-rotation on map containers to create a 3D isometric view, reinforcing the "world-building" aspect of the platform.