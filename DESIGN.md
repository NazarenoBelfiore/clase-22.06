---
name: Organic Vanguard
colors:
  surface: '#1b110e'
  surface-dim: '#1b110e'
  surface-bright: '#433633'
  surface-container-lowest: '#150c09'
  surface-container-low: '#241916'
  surface-container: '#281d1a'
  surface-container-high: '#332724'
  surface-container-highest: '#3e322e'
  on-surface: '#f3ded9'
  on-surface-variant: '#d4c3bd'
  inverse-surface: '#f3ded9'
  inverse-on-surface: '#3a2e2a'
  outline: '#9c8e88'
  outline-variant: '#504440'
  surface-tint: '#e5beaf'
  primary: '#e5beaf'
  on-primary: '#432b20'
  primary-container: '#4a3126'
  on-primary-container: '#bc988a'
  inverse-primary: '#75584b'
  secondary: '#ffb693'
  on-secondary: '#561f00'
  secondary-container: '#fe6b00'
  on-secondary-container: '#572000'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#353737'
  on-tertiary-container: '#9fa0a0'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#e5beaf'
  on-primary-fixed: '#2b160d'
  on-primary-fixed-variant: '#5c4135'
  secondary-fixed: '#ffdbcc'
  secondary-fixed-dim: '#ffb693'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7a3000'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#1b110e'
  on-background: '#f3ded9'
  surface-variant: '#3e322e'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 84px
    fontWeight: '700'
    lineHeight: 90%
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 100%
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 110%
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 160%
    letterSpacing: 0em
  label-mono:
    fontFamily: Space Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 140%
    letterSpacing: 0.1em
  data-point:
    fontFamily: Space Mono
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 120%
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  edge-margin: clamp(2rem, 8vw, 8rem)
  section-gap: clamp(4rem, 15vh, 12rem)
  internal-gap: 1.5rem
  technical-grid: 0.5rem
---

## Brand & Style

This design system embodies a premium, cinematic editorial aesthetic tailored for the Venzo Amphion. The narrative focuses on "Organic Vanguard"—a tension between raw, earthy foundations and precision-engineered technology. The emotional response is one of sophisticated adventure: grounded, yet hyper-modern.

The visual style leans into **Minimalism** with an **Editorial** rhythm. It avoids traditional UI clutter, favoring vast negative space to allow the product photography to breathe. Transitions between content blocks should feel fluid and intentional, mirroring the cadence of a high-end physical lookbook.

## Colors

The palette is anchored in **Warm Earth Brown (#4a3126)**, serving as the primary immersive background. This creates a rich, "soil-to-soul" atmosphere. 

**Vibrant Orange (#ff6b00)** is used with extreme restraint—only for critical calls to action or performance highlights—to maintain a premium feel. 

The design employs a high-contrast alternating block strategy:
- **Primary Mode:** Warm Earth Brown background with Pure White typography.
- **Inverted Mode:** Pure White background with Dark Brown (#1e1411) typography for technical or "bright-room" editorial sections.

## Typography

The typography strategy leverages the structural precision of **Space Grotesk** for emotional storytelling and **Space Mono** for technical data.

- **Headlines:** Set in Space Grotesk with tight tracking and a "tight-stack" line height to create an impactful, graphic silhouette.
- **Labels:** Technical specifications, frame geometry, and metadata utilize Space Mono to evoke a sense of engineering blueprints.
- **Asymmetry:** Headlines should frequently be offset or placed in unconventional quadrants of the screen to support the "no-grid" editorial feel.

## Layout & Spacing

This design system abandons the rigid 12-column grid in favor of a **fluid editorial model**. Elements are positioned relative to the viewport edges and organic focal points within imagery.

- **Vast Negative Space:** Content sections are separated by significant vertical gaps to ensure a slow, premium scrolling experience.
- **Asymmetric Offsets:** Layouts should alternate between left-aligned text blocks and right-aligned imagery to maintain visual dynamism.
- **Technical Overlays:** While the main layout is fluid, technical data points (using Space Mono) can be pinned to specific areas of a bicycle image using a 4px precise sub-grid.

## Elevation & Depth

To maintain a clean, avant-garde look, the system avoids traditional drop shadows. Depth is instead communicated through:

- **Tonal Layering:** Using slightly lighter or darker variations of the primary Earth Brown to distinguish interface layers.
- **Scale and Parallax:** Product components (like the frame or drivetrain) may float over the background with subtle parallax movement to create a 3D sensation.
- **Soft Blurs:** Background blurs are used only for navigation overlays to maintain legibility without breaking the "one-surface" aesthetic.

## Shapes

The shape language reflects the industrial design of the Venzo Amphion—functional and sharp, but naturally refined.

- **Primary Radius:** Use a "Soft" (0.25rem) radius for standard UI elements like input fields or smaller cards. This provides a human touch without appearing "bubbly."
- **Interactive Elements:** Buttons and interactive hotspots should remain subtly softened to distinguish them from the sharp edges of technical diagrams.
- **Clipping:** Editorial imagery may use organic, asymmetrical clipping masks to blend the photography into the background color.

## Components

### Buttons
Primary buttons are solid White or Orange with Dark Brown text. No border, "Soft" roundedness. Label is in Space Mono for a technical, high-performance look.

### Chips / Technical Labels
Used for bike specs (e.g., "Carbon T1000"). Rendered in Space Mono with a thin (1px) white outline and 0% background fill.

### Performance Data
Cards for technical data should have no background color. They rely on Space Mono typography and thin vertical "separator" lines to organize information.

### Navigation
A minimalist persistent bar. Text links only, no icons, using Space Grotesk in a small, semi-bold weight.

### Image Hotspots
Small, glowing Orange (#ff6b00) points that, when hovered, expand into a technical data flyout using the Inverted (Pure White) background mode.