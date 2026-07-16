---
name: Heritage Hearth
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1c1c'
  surface-container: '#1f2020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e4e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e4e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c8c6c5'
  primary: '#c8c6c5'
  on-primary: '#313030'
  primary-container: '#121212'
  on-primary-container: '#7e7d7d'
  inverse-primary: '#5f5e5e'
  secondary: '#ffb3b3'
  on-secondary: '#512123'
  secondary-container: '#6d3738'
  on-secondary-container: '#eba2a2'
  tertiary: '#ccc6b5'
  on-tertiary: '#333124'
  tertiary-container: '#141208'
  on-tertiary-container: '#817d6e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ffb3b3'
  on-secondary-fixed: '#370d10'
  on-secondary-fixed-variant: '#6d3738'
  tertiary-fixed: '#e8e2d0'
  tertiary-fixed-dim: '#ccc6b5'
  on-tertiary-fixed: '#1e1c11'
  on-tertiary-fixed-variant: '#4a4739'
  background: '#131313'
  on-background: '#e4e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Libre Caslon Text
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
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is built for a brand that bridges 1960s Italian-Costa Rican heritage with a premium, modern dining experience. The personality is nostalgic yet sophisticated, evoking the atmosphere of a dimly lit, upscale trattoria. 

The visual style utilizes a **Modern-Vintage** approach. It leans into a refined dark mode that prioritizes high-quality food photography and elegant typography over complex UI ornaments. The emotional response should be one of "Affordable Luxury"—feeling established, warm, and trustworthy. We avoid digital "slickness" in favor of organic, tactile quality, using subtle grain and high-contrast editorial layouts.

## Colors

The palette is centered on a deep, rich foundation to allow food imagery to "pop." 

- **Primary (Deep Charcoal):** Used for the primary canvas. It is not a pure black, but a warm charcoal that feels more organic and less clinical.
- **Secondary (Pastel Red):** A desaturated, sophisticated red used for calls to action, highlights, and price points. It nods to traditional tomato sauce without being aggressive.
- **Tertiary (Pastel Cream):** Used for primary typography and borders. This off-white provides a vintage paper feel and reduces eye strain compared to pure white.
- **Surface Tones:** Middle-greys and deep browns are used for containers to maintain the "dark room" aesthetic.

## Typography

This design system uses a high-contrast typographic pairing. **Libre Caslon Text** brings a literary, historical authority to headlines, mimicking vintage Italian menus and newspapers. **Manrope** provides a clean, modern counter-balance for functional text, ensuring legibility on mobile devices and during the ordering process.

All labels and captions should use Manrope with increased letter spacing to enhance the "designed" look of the UI. Headlines should use tight tracking to maintain a strong, editorial presence.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous margins to create an "airy" and premium feel. 

- **Desktop:** A 12-column grid with a 1280px max-width. Content is often centered with wide "safe zones" on the flanks to mimic a printed book layout.
- **Mobile:** A 4-column grid. Padding is increased around food items to give them visual "breathing room."
- **Spacing Rhythm:** Based on an 8px scale. Use larger gaps (48px+) between distinct menu sections to reinforce a relaxed, non-cluttered browsing experience.

## Elevation & Depth

To maintain the vintage-modern aesthetic, this design system avoids heavy drop shadows. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Levels:** The base background is the darkest. Cards and modals use a slightly lighter charcoal (#1A1A1A).
- **Outlines:** Instead of shadows, use 1px borders in Pastel Cream at 10-15% opacity to define container edges.
- **Photography:** Images are the primary source of depth. Use subtle vignettes and deep blacks within food photography to make items feel like they are emerging from the interface.

## Shapes

The design system utilizes **Soft** roundedness. While the brand is traditional, sharp corners feel too "aggressive" or "institutional," and fully rounded pills feel too "tech." 

The 0.25rem (4px) base radius provides a subtle hint of craft and hand-finished quality, similar to a cut piece of heavy cardstock or a vintage photograph. Larger containers like cards may use the `rounded-lg` (8px) setting to feel more approachable.

## Components

- **Buttons:** Primary buttons use the Pastel Red background with the Charcoal text. They are rectangular with a 4px radius. Secondary buttons use a Pastel Cream outline with no fill.
- **Input Fields:** Minimalist design. Only a bottom border in Pastel Cream (40% opacity) or a very subtle dark-grey fill. Labels sit above the field in Manrope Bold (Label-sm).
- **Cards:** Used for menu items. Cards should have no background or a very subtle dark-grey fill. The focus is on a high-resolution image followed by a Caslon headline.
- **Chips/Badges:** Use Pastel Cream text on a deep charcoal background with a 1px Pastel Cream border for tags like "Vegetarian" or "Spicy."
- **Lists:** Menu lists use a "leader" style (dots connecting the item name to the price), reinforcing the classic Italian pizzeria aesthetic.
- **Dividers:** Use thin, 1px lines in Pastel Cream at low opacity. Occasionally use a decorative "asterisk" or "diamond" glyph to separate major sections.