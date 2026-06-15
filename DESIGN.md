---
name: Serene Editorial
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeea'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#434842'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f1ed'
  outline: '#737972'
  outline-variant: '#c3c8c0'
  surface-tint: '#4d6450'
  primary: '#4d6450'
  on-primary: '#ffffff'
  primary-container: '#88a089'
  on-primary-container: '#223725'
  inverse-primary: '#b4cdb4'
  secondary: '#4c616b'
  on-secondary: '#ffffff'
  secondary-container: '#cfe6f2'
  on-secondary-container: '#526771'
  tertiary: '#845321'
  on-tertiary: '#ffffff'
  tertiary-container: '#c88d56'
  on-tertiary-container: '#4d2900'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9cf'
  primary-fixed-dim: '#b4cdb4'
  on-primary-fixed: '#0b2010'
  on-primary-fixed-variant: '#364c39'
  secondary-fixed: '#cfe6f2'
  secondary-fixed-dim: '#b4cad5'
  on-secondary-fixed: '#081e27'
  on-secondary-fixed-variant: '#354a53'
  tertiary-fixed: '#ffdcc0'
  tertiary-fixed-dim: '#fab97e'
  on-tertiary-fixed: '#2d1600'
  on-tertiary-fixed-variant: '#683c0a'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e3e2df'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
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
  unit: 8px
  container-max: 1140px
  gutter: 24px
  margin-mobile: 20px
  section-padding: 80px
---

## Brand & Style

The brand identity for Mariana Fontaneta is built upon the concept of "Ethereal Professionalism." This design system balances the clinical authority required for a psychologist with the soft, high-end aesthetic of luxury editorial design. The target audience is women seeking a safe, premium space for mental wellness that feels more like a sanctuary than a clinic.

The visual style is a blend of **Minimalism** and **Tactile Sophistication**. It utilizes generous white space (negative space) to reduce cognitive load and evoke a sense of calm. The presence of subtle organic depth through soft shadows and layered elements creates a human, approachable atmosphere. Every interaction should feel intentional, quiet, and refined, reflecting the personal and sensitive nature of psychotherapy.

## Colors

The palette is derived from nature and soft textiles, designed to lower cortisol and invite openness.

- **Sage Green (Primary):** Used for primary brand elements, active states, and headings. It represents growth, stability, and restoration.
- **Dusty Blue (Secondary):** Used for interactive supporting elements and calming backgrounds. It adds a layer of professional serenity.
- **Warm Terracotta (Accent):** Used sparingly for call-to-actions or "human" highlights. It provides a grounded, earth-toned warmth.
- **Light Beige (Background):** Replacing harsh whites, this off-white tone provides a paper-like, editorial feel that is easier on the eyes.
- **Blush Pink (Detail):** A decorative accent for subtle dividers, icons, or soft hover states.

## Typography

This design system uses a high-contrast typographic pairing to achieve a boutique editorial look.

- **Headlines (Playfair Display):** This transitional serif brings elegance and a sense of "history" and trust. It should be used for all H1–H3 tags. Large display text should use a slightly tighter letter spacing for a modern fashion-spread appearance.
- **Body & UI (Manrope):** A clean, humanist sans-serif that ensures accessibility and legibility. Its geometric roots keep the design feeling contemporary without becoming cold. 
- **Language Nuance:** Since the content is in Brazilian Portuguese, line heights are slightly increased to accommodate common diacritics (til, cedilha) and longer word structures without feeling crowded.

## Layout & Spacing

The design follows a **fixed grid** model for desktop to maintain the integrity of the editorial layout, and a fluid model for mobile devices.

- **The Breathable Rhythm:** Spacing is generous. Sections are separated by large vertical gaps (80px–120px) to allow the user to process information at a slow, meditative pace.
- **Grid:** A 12-column grid is used for desktop. Content often occupies the central 8 columns to create wide "luxury" margins.
- **Mobile:** Transition to a 4-column grid with 20px side margins. Elements that are side-by-side on desktop (like cards) should stack vertically on mobile to maintain readability and touch-target size.

## Elevation & Depth

To avoid a "flat" corporate feel, the design system utilizes **Ambient Shadows** and **Tonal Layers**.

- **Shadows:** Use extremely diffused shadows with a low opacity (8-10%) and a slight tint of the Primary Sage Green or Dusty Blue. This makes elements look like they are resting softly on a textile surface rather than floating in digital space.
- **Depth Hierarchy:**
  - **Level 0 (Base):** Light Beige background.
  - **Level 1 (Cards):** Soft White or very light Sage/Blue tint with a 1px border (#E5E5E5) or a soft shadow.
  - **Level 2 (Modals/Popovers):** Higher blur radius (30px+) and a subtle backdrop blur (4px) to create a focused, intimate moment for the user.

## Shapes

The shape language is organic and soft. 

- **Corners:** Standard UI elements like buttons and input fields use a `0.5rem` radius. 
- **Cards & Hero Images:** Use a more pronounced `1.5rem` (rounded-xl) to emphasize a "cradled" and safe feeling.
- **Decorative Elements:** Circular crops for profile photos of Mariana Fontaneta or abstract wellness photography are encouraged to break the rigidity of the grid.

## Components

- **Buttons:** Primary buttons use a solid Sage Green background with white text. Secondary buttons use a Sage Green outline with a subtle background hover of Blush Pink. Use "Ghost" buttons with Playfair Display for "Read More" links.
- **Input Fields:** Use a minimalist approach with a bottom border only or a very light off-white fill. Label typography should be `label-sm` in all caps with tracking.
- **Cards:** Utilize a "floating" style—no heavy borders, just a subtle shadow and the Light Beige background. Content inside cards should have generous padding (32px+).
- **Chips/Tags:** Used for therapy specializations (e.g., "Ansiedade", "Autoestima"). These should be Pill-shaped with Dusty Blue or Sage Green light fills and dark text.
- **Quotes:** A specific component for patient testimonials or therapeutic insights, featuring large terracotta serif quotation marks and italicized Playfair Display text.
- **Booking Widget:** A specialized floating card that stays persistent or easily accessible, using the Warm Terracotta for the "Agendar Consulta" (Book Appointment) button to ensure it is the focal point.