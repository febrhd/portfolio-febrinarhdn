---
name: Neo-Glitch Retro Brutalist
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#3e4942'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#6e7a71'
  outline-variant: '#bdcac0'
  surface-tint: '#006c47'
  primary: '#006b47'
  on-primary: '#ffffff'
  primary-container: '#00875a'
  on-primary-container: '#ffffff'
  inverse-primary: '#71dba6'
  secondary: '#ab2c5f'
  on-secondary: '#ffffff'
  secondary-container: '#fd6c9e'
  on-secondary-container: '#6e0036'
  tertiary: '#9b403e'
  on-tertiary: '#ffffff'
  tertiary-container: '#ba5855'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#8df7c1'
  primary-fixed-dim: '#71dba6'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005235'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c6'
  on-secondary-fixed: '#3f001c'
  on-secondary-fixed-variant: '#8b0e47'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3af'
  on-tertiary-fixed: '#410005'
  on-tertiary-fixed-variant: '#7d2a2a'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '900'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '900'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '800'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Archivo Narrow
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.5'
  body-md:
    fontFamily: Archivo Narrow
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-bold:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system draws inspiration from the Y2K aesthetic fused with modern Brutalism. It targets a Gen-Z audience by balancing nostalgia with high-performance digital utility. The personality is unapologetically loud, playful, and energetic, yet grounded by a structured grid system that ensures professional reliability.

The visual direction utilizes high-contrast outlines, "sticker-slap" layering techniques, and a deliberate disregard for traditional soft shadows in favor of hard-edged depth. Expect frequent use of starbursts, asterisks, and scrolling marquee ribbons to create a sense of constant motion and discovery.

## Colors

The palette is anchored by a soft pastel cream-pink background which prevents the high-contrast elements from feeling overly clinical. The **Primary Emerald Green** is used for action-oriented elements and success states, while the **Secondary Playful Pink** is reserved for highlights, starbursts, and interactive accents. 

Black (#1A1A1A) is used aggressively for thick 2px and 4px borders, creating the "sticker" effect. All interactive elements must maintain a high contrast ratio against the pastel base.

## Typography

Typography is a primary structural element in this design system. 
- **Headlines:** Use Montserrat at its heaviest weights (800-900). For display text, use tight tracking to emphasize the "blocky" brutalist feel.
- **Body:** Archivo Narrow provides a condensed, efficient feel that contrasts with the wide headlines, mimicking print editorial layouts.
- **System Labels:** Space Grotesk is used for technical data, buttons, and badges to lean into the Y2K "tech-optimism" aesthetic.

## Layout & Spacing

The layout follows a strict 12-column fluid grid for desktop and a 4-column grid for mobile. Unlike minimalist designs, whitespace here is often filled with "texture" such as marquee text or repeating geometric patterns. 

Elements are spaced using a 4px baseline grid. Large sections should be separated by thick horizontal ribbons (32px - 48px height) containing scrolling text or repetitive icons. Components should often "break" the grid slightly—overlapping or stacking with hard offsets to create a collage-like appearance.

## Elevation & Depth

This design system rejects ambient soft shadows. Depth is achieved through **Hard-Edge Offsets**:
- **Level 1:** 2px solid black border with no offset.
- **Level 2:** 2px solid black border with a 4px black drop-shadow (0% blur).
- **Level 3 (Active):** 2px solid black border with an 8px offset shadow in either the Primary Green or Secondary Pink.

Interactive surfaces should appear as "Physical Cards" or "Stickers." Use background blurs only within "Windows" (modal overlays) to reference early 2000s OS interfaces, but maintain the thick black border surrounding the blur.

## Shapes

The design system uses a **Sharp (0)** roundedness philosophy for the majority of structural containers to maintain the Brutalist edge. 

Exceptions are made for:
- **Buttons:** Can be fully pill-shaped to contrast against sharp cards.
- **Stickers:** Starbursts and 8-point asterisks are used for callouts and price tags.
- **Images:** Always framed with a 2px black border. Occasionally use a "bracket" corner style for image frames.

## Components

### Buttons
Primary buttons use the Emerald Green background with a 2px black border and a 4px black hard shadow. On hover, the shadow should "shrink" (0px offset) to simulate a physical press.

### Marquee Ribbons
Horizontal bars that span the full width of the viewport. These contain auto-scrolling text in `label-bold` typography, used for announcements or navigational highlights.

### Cards
Cards are the primary container. They use the pastel pink background or pure white, always with a 2px black border. Use "Sticker" badges (starbursts) overlapping the top-right corner of cards for status updates.

### Input Fields
Inputs are rectangular with sharp 0px corners. Use a thick 2px border. Focus state changes the border color to Primary Emerald and adds a hard 4px offset shadow.

### Checkboxes & Radios
Custom-styled as large squares (checkboxes) or diamonds (radios). When checked, they fill with the Secondary Pink and a black "X" or "Dot" mark.

### Lists
Lists are separated by 2px black horizontal rules. Each list item should have a hover state that shifts the entire background to Primary Emerald and the text to white.