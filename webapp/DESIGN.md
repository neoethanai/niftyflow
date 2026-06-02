---
name: Aethelgard AI
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
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#bfcdff'
  on-tertiary: '#082b72'
  tertiary-container: '#97b0ff'
  on-tertiary-container: '#254188'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#27438a'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  obsidian-deep: '#050505'
  charcoal-surface: '#0A0A0A'
  champagne-gold: '#D4AF37'
  starlight-white: '#F1F5F9'
  glass-border: rgba(212, 175, 55, 0.15)
  subtle-ash: '#94A3B8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 4.5rem
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 2.75rem
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '300'
    lineHeight: '1.8'
    letterSpacing: 0.01em
  body-default:
    fontFamily: Inter
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.25em
  button-text:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1440px
  section-gap: 10rem
  section-gap-mobile: 5rem
  element-gap: 2rem
  grid-gutter: 2.5rem
  safe-margin: 2rem
---

## Brand & Style

The design system is engineered for an elite AI Automation Agency, targeting C-suite executives and founders who demand precision, exclusivity, and technological mastery. The personality is "Architectural Intelligence"—a blend of silent power and surgical accuracy. 

The visual style is **Minimalist-Glassmorphic**. It utilizes deep, infinite blacks and charcoal foundations to make champagne gold accents feel earned and authoritative. The aesthetic prioritizes "breathability" and vast whitespace to signal high-value consulting, avoiding the cluttered layouts of typical tech startups. Every element is designed to feel like a high-end luxury watch or a bespoke architectural interior: thin, precise, and structurally sound.

## Colors

The palette is anchored in **Obsidian Deep (#050505)** for the canvas, providing a void-like depth that emphasizes foreground elements. **Charcoal Surface (#0A0A0A)** is used for subtle layering and container separation.

**Champagne Gold (#D4AF37)** is the primary hallmark. It must be used sparingly for high-impact CTAs, critical data points, and sophisticated accents. To maintain a premium feel, gradients should be extremely subtle, moving from a muted gold to a more vibrant champagne. **Starlight White** serves as the primary text color, ensuring clinical legibility against the dark void.

## Typography

The typography strategy relies on the tension between the classic, editorial elegance of **Playfair Display** and the functional, technical precision of **Inter**. 

- **Headlines:** Use Playfair Display for all major headings. It signals heritage and high-touch service.
- **Body Text:** Use Inter with a Light (300) or Regular (400) weight. Increase line-height to 1.8 for larger blocks of text to maximize readability and "air."
- **Labels:** Small labels and "over-titles" should always be in Inter, uppercase, with significant letter spacing (20-25%) to create a technical, "scanned" aesthetic.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop, centered on a 1440px canvas with a 12-column structure. 

The defining characteristic is **extreme vertical rhythm**. Sections are separated by a massive 10rem (160px) gap to prevent the AI automation content from feeling "busy" or overwhelming. 

**Reflow Rules:**
- **Desktop:** 12 columns, 40px gutters.
- **Tablet:** 8 columns, 24px gutters, 4rem section gaps.
- **Mobile:** 4 columns, 16px gutters, 5rem section gaps. Hero text scales down significantly to ensure elegant line breaks.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Glassmorphism**, rather than traditional heavy shadows. 

1.  **The Base:** Obsidian (#050505).
2.  **The Surface:** Charcoal (#0A0A0A) used for cards, with a 1px border of `glass-border`.
3.  **The Glass:** For interactive elements, use `backdrop-filter: blur(20px)` with a 5% white opacity fill.
4.  **Soft Glows:** High-priority cards or active states may use a "Golden Aura"—a very low-opacity (8%) gold outer glow with a 40px spread to simulate a soft internal light source.
5.  **Hairline Borders:** All borders must be 1px. Thicker borders are prohibited as they break the luxury aesthetic.

## Shapes

The shape language is **Soft (0.25rem)**. This slight rounding provides just enough modern approachability without losing the rigorous, professional edge of sharp corners.

- **Standard Containers:** 0.25rem (4px).
- **Cards & Modals:** 0.5rem (8px).
- **Pill Elements:** Reserved strictly for status tags and specific "High-Tech" badges.
- **Buttons:** 2px radius (near-sharp) to maintain a bespoke, tailored look.

## Components

### Buttons
- **Primary:** Champagne gold background with black text. No shadows. Sharp 2px radius. 
- **Secondary/Ghost:** 1px champagne gold border, transparent background, white text. 
- **Hover State:** Primary buttons should subtly increase in brightness; Ghost buttons should fill with 5% gold opacity.

### Cards
- Background: Charcoal Surface (#0A0A0A).
- Border: 1px `glass-border`.
- Padding: 3rem (48px) to emphasize the premium nature of the content.

### Input Fields
- Underline style preferred over boxed inputs. 
- 1px `subtle-ash` bottom border that turns `champagne-gold` on focus.
- Labels are always small caps above the field.

### Chips & Badges
- Used for AI model tags or service categories.
- Minimalist: 1px border, no background, 0.75rem Inter text.

### Refined Transitions
- All interactions must use a `0.4s cubic-bezier(0.16, 1, 0.3, 1)` transition for a "heavy" yet smooth feel that mimics high-end hardware.