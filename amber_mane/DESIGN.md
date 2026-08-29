---
name: Amber Mane
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#554336'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#887364'
  outline-variant: '#dbc2b0'
  surface-tint: '#904d00'
  primary: '#8d4b00'
  on-primary: '#ffffff'
  primary-container: '#b15f00'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb77d'
  secondary: '#725a42'
  on-secondary: '#ffffff'
  secondary-container: '#fedcbe'
  on-secondary-container: '#796048'
  tertiary: '#825100'
  on-tertiary: '#ffffff'
  tertiary-container: '#a36700'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc3'
  primary-fixed-dim: '#ffb77d'
  on-primary-fixed: '#2f1500'
  on-primary-fixed-variant: '#6e3900'
  secondary-fixed: '#fedcbe'
  secondary-fixed-dim: '#e1c1a4'
  on-secondary-fixed: '#291806'
  on-secondary-fixed-variant: '#59422c'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  headline-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system embodies a "fandom-professional" aesthetic—a sophisticated blend of clean, functional layouts with the spirited, organic warmth of the character 'Caju'. The brand personality is energetic, welcoming, and deeply expressive, balancing the structured efficiency of a modern SaaS product with the playful tactile nature of character-driven design.

The visual style is **Corporate Modern with Tactile influences**. It utilizes high-quality whitespace and professional alignment but breaks the rigid grid with organic, "fur-tuft" shaped containers and soft, exaggerated roundedness. The goal is to evoke a sense of creative community, reliability, and spirited charm.

## Colors

The palette is derived directly from the character's natural tones, creating a high-contrast yet warm environment.

*   **Primary (Ginger Orange):** A rich, energetic orange used for calls to action, active states, and brand highlights.
*   **Secondary (Deep Bark):** A sophisticated dark brown used for primary text, deep borders, and grounding elements, providing a softer alternative to pure black.
*   **Tertiary (Golden Eye):** A bright, sunny amber used for accents, warning states, or decorative elements like highlights.
*   **Neutral (Cream Fur):** A soft, warm off-white used for backgrounds to reduce eye strain and maintain the "warm" brand promise.
*   **Accent (Blush Heart):** A soft coral/red (#FB7185) should be used sparingly for destructive actions or "like" interactions, mirroring the heart motifs.

## Typography

The typography strategy pairs a high-personality display face with a clean, modern sans-serif to ensure legibility without losing character.

**Bricolage Grotesque** is the voice of the brand. Its quirky, variable-width appearance and expressive terminals mirror the character's hair and dynamic movement. Use this for all headlines and large pull-quotes.

**Plus Jakarta Sans** provides a friendly, geometric foundation for body copy. It is highly readable at small sizes while maintaining a "soft" feel that complements the overall aesthetic.

For emphasis within body text, use the SemiBold weight of Plus Jakarta Sans in the Secondary (Deep Bark) color.

## Layout & Spacing

The layout follows a **fluid grid system** with generous margins to allow the "organic" shapes room to breathe. 

*   **Desktop:** 12-column grid with 24px gutters. Content should be centered within a 1280px max-width container.
*   **Tablet:** 8-column grid with 20px gutters.
*   **Mobile:** 4-column grid with 16px gutters and 20px side margins.

Spacing should follow an 8px base unit. Use larger "breathable" gaps (48px+) between major sections to emphasize a premium, clean feel. Elements like cards or image containers should use asymmetrical padding (e.g., more padding at the bottom than the top) to mimic the weighted look of the character's silhouette.

## Elevation & Depth

This system avoids heavy shadows in favor of **Tonal Layers and Character Outlines**. 

Visual hierarchy is achieved by stacking "Cream Fur" surfaces on top of slightly darker neutral backgrounds. To define depth, use a "thicker" stroke (2px) in the Secondary color for primary interactive elements, mimicking the bold line-art of the character. 

Low-elevation elements (like secondary cards) should use a subtle 1px border in a muted version of the Secondary color instead of a shadow. High-elevation elements (like Modals) may use a soft, tinted ambient shadow: `0px 10px 30px rgba(75, 54, 33, 0.08)`.

## Shapes

The shape language is "Hyper-Rounded." While the base roundedness is set to `2` (0.5rem), this design system frequently employs **asymmetrical rounding** to create "tuft" effects. 

*   **Standard UI:** 0.5rem (8px) for buttons and inputs.
*   **Large Cards:** 1.5rem (24px) for most corners, with a "signature" corner (top-right or bottom-left) pushed to 3rem (48px) to create a leaf-like or fur-like silhouette.
*   **Iconography:** Icons should feature rounded caps and corners, avoiding any sharp 90-degree angles.

## Components

### Buttons
*   **Primary:** Solid Primary Orange background, Secondary Brown text, Bold weight. 8px corner radius.
*   **Secondary:** Cream background with a 2px Secondary Brown border.
*   **Hover State:** Increase the corner radius slightly (from 8px to 12px) to create a "squishy" tactile feel.

### Cards
*   Use the asymmetrical rounding mentioned in the Shapes section.
*   Background should be pure White or the lightest "Cream Fur" neutral.
*   Add a subtle 1px inset border to give the card a "pressed" look.

### Input Fields
*   Background: White.
*   Border: 2px solid Secondary Brown on focus; 1px soft brown when inactive.
*   Labels: Always placed above the field in Label-MD style.

### Chips & Tags
*   Pill-shaped (3rem roundedness). 
*   Use Tertiary Golden for status or "featured" items.
*   Add a small "dot" icon to the left of the text to mimic a nose or paw print.

### Progress Bars
*   Thick (12px) tracks with fully rounded caps. 
*   The "filler" should use a subtle gradient from Primary Orange to Tertiary Golden.