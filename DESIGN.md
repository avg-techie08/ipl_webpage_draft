---
name: Pitch Arena
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#5c403a'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#906f69'
  outline-variant: '#e5beb6'
  surface-tint: '#ba1b00'
  primary: '#b61b00'
  on-primary: '#ffffff'
  primary-container: '#db3417'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a5'
  secondary: '#785900'
  on-secondary: '#ffffff'
  secondary-container: '#fcc019'
  on-secondary-container: '#6c5000'
  tertiary: '#5a5c5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#737575'
  on-tertiary-container: '#fcfcfc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a5'
  on-primary-fixed: '#3f0400'
  on-primary-fixed-variant: '#8e1300'
  secondary-fixed: '#ffdf9d'
  secondary-fixed-dim: '#f9bd14'
  on-secondary-fixed: '#251a00'
  on-secondary-fixed-variant: '#5b4300'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 84px
    fontWeight: '400'
    lineHeight: 84px
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 60px
    letterSpacing: 0.01em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.01em
  headline-md:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-bold:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-badge:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system delivers an intense, high-energy neo-brutalist identity for a competitive collegiate pitch league. Merging the spectacle of high-stakes sports arenas with engineering rigor and entrepreneurial grit, the aesthetic discards tech-startup gloss in favor of punchy, high-contrast, physical paper-and-ink visual authority.

### Core Tenets
- **Raw Physicality:** Every interactive component feels stamped onto heavy cardstock. Thick strokes, unblurred hard-edge drop shadows, and sharp spatial offsets simulate tactile mechanical interaction.
- **Electric Competition:** Visual hierarchy drives adrenaline. Information is delivered through heavy typographic scales, sticker-like tags, and assertive contrasts.
- **Unapologetic Clarity:** No blurs, no gradients, no translucent overlays. Every element exists on a distinct, opaque plane defined by uncompromising 3px ink borders.

## Colors

The palette relies on deliberate, high-contrast color roles to guide attention under an aggressive neo-brutalist paradigm:

- **Base / Canvas (`#FFF8E7`):** Warm cream newsprint base tone. Acts as the primary surface across all standard card backgrounds and page sections, softening raw optical contrast while maintaining a vintage tournament print feel.
- **Ink / Structure (`#121212`):** Pure dense carbon. Used for all primary borders (3px solid), drop shadows, high-emphasis copy, and micro-framing lines.
- **Primary Energy Accent (`#FF4D2E`):** Flat blistering orange-red. Reserved strictly for conversion-focused actions (CTAs), registration countdown elements, live status indicators, and active selection states.
- **Secondary Accent (`#F2B705`):** Flat tournament gold. Dedicated solely to prize pool figures, trophy indicators, podium labels, and monetary callouts. It must never compete with primary action buttons.
- **Surface Contrast White (`#FFFFFF`):** Pure bleached container backing, used sparingly to make select cards or input fields pop off the warm cream background.

## Typography

Typography establishes an athletic and technical match-day broadcast feeling. 

- **Display & Headlines (Anton):** Chosen for its heavy, condensed presence. Used strictly in uppercase for section banners, giant team numbers, cash figures, and event dates. It commands horizontal space with zero hesitation.
- **Body & Interface (Hanken Grotesk):** Built for crisp readability against high-contrast backgrounds. Weights 500 (standard content), 600 (lead paras), and 700 (sub-headers, metadata keys) prevent visual washout against thick borders.
- **Data, Metadata & Code (JetBrains Mono):** Set in weight 600. Employed for timestamps, pitch rounds, technical eligibility rules, ticker bands, and team ID badges. All mono labels render in all-caps.

## Layout & Spacing

Layouts follow an architectural, modular column system inspired by newspapers and bracket posters.

### Layout Philosophy
- **Modular Fluid Grid:** 12-column setup for desktop (1024px+), collapsing to 6-column on tablet (768px–1023px), and 4-column on mobile (<768px). Sections are demarcated by horizontal 3px ink rules rather than empty white space.
- **Margin & Safe Zones:** Canvas margins stay robust at `2rem` (desktop) and reduce to `1rem` on mobile. Containers emphasize full-bleed dividers and bold boxed framing over centered floating layouts.
- **Density Rhythm:** Component internal padding uses consistent steps (`space-md` for standard cards, `space-lg` for marquee feature cards). Vertical spacing between blocks is structured with deliberate content heft—dense, packed, and punchy.

## Elevation & Depth

Visual hierarchy uses hard physical displacement. Gaussian blurs, soft glows, and translucent overlays are strictly prohibited.

- **Rest Elevation:** All elevated surfaces (buttons, cards, banners) apply a rigid, opaque drop shadow: `box-shadow: 6px 6px 0px #121212`.
- **Hover / Interactive Elevation:** Interactive surfaces translate up and to the left by 4px, expanding the shadow footprint: `transform: translate(-4px, -4px); box-shadow: 10px 10px 0px #121212`.
- **Active / Depressed Elevation:** On mouse click or tap active states, the component compresses directly into the shadow origin: `transform: translate(6px, 6px); box-shadow: 0px 0px 0px #121212`.
- **Flat Ground Plane:** Structural dividers, tables, and informational ribbons remain completely flat with 3px solid `#121212` perimeter strokes without shadows.

## Shapes

The design system employs a consistent border radius to create a sticker-like, graphic-novel feel across all components:

- **Global Standard Radius:** All buttons, interactive cards, badge tags, and input boxes use `8px` (`0.5rem`) border radiuses.
- **Border Weight:** Universally locked at `3px solid #121212`. Inner dividers within cards or nested modules drop to `2px solid #121212`.
- **Corner Discipline:** No pills or full round circles except for compact status dots or circular badge stamps. Sharp visual rhythm is maintained through rectangular, structured silhouettes.

## Components

### Buttons
- **Primary Action Button:** Background `#FF4D2E`, text `#121212`, 3px solid `#121212` border, 8px radius. Rest shadow `6px 6px 0px #121212`. Hover state lifts to `10px 10px 0px #121212` with `-4px, -4px` offset. Active state pushes down to `translate(6px, 6px)` with zero shadow. Font: JetBrains Mono or Hanken Grotesk 700, uppercase.
- **Secondary / Neutral Button:** Background `#FFF8E7`, text `#121212`, identical 3px border, 8px radius, and physical offset hover/active dynamics.
- **Trophy / Prize CTA:** Background `#F2B705`, text `#121212`, identical borders and shadow physics.

### Cards & Panels
- **Standard Card:** Background `#FFF8E7` or `#FFFFFF`, 3px solid `#121212` border, 8px radius, `6px 6px 0px #121212` shadow. Header sections inside cards are separated by a 3px horizontal border line.
- **Prize Card:** Highlighted container with a `#F2B705` accent banner bar at the top, bold mono prize sum, and an outline stamp graphic.

### Chips & Badges
- **Status Badges:** JetBrains Mono 12px uppercase, padding `4px 10px`, 8px radius, 2px solid `#121212`.
- **Live / Urgency Tag:** Background `#FF4D2E`, text `#FFF8E7`.
- **Category Tag:** Background `#FFF8E7`, text `#121212`, flat without drop shadow.

### Inputs & Forms
- **Text Inputs:** Background `#FFFFFF`, 3px solid `#121212`, 8px radius, padding `12px 16px`. Font: Hanken Grotesk 600.
- **Input Focus State:** Retains 3px solid `#121212` border, drops a `4px 4px 0px #FF4D2E` solid shadow. No outline glows.

### Checkboxes & Radio Buttons
- **Checkboxes:** Custom square 22x22px, 3px solid `#121212`, 4px radius. When checked, background fills with `#FF4D2E` containing a thick `#121212` geometric checkmark.
- **Radio Buttons:** 22x22px circular housing with 3px solid `#121212`. Active state reveals an inner solid `#121212` circle.

### Specialized Event Components
- **Marquee Ticker Band:** Solid `#121212` background, text `#FFF8E7` or `#F2B705`, continuous horizontal scroll of league rules, dates, and sponsor handles in JetBrains Mono.
- **Leaderboard / Fixture Row:** Dense `#FFF8E7` horizontal slab bordered by 3px solid `#121212`, hovering into a `#FF4D2E` micro-highlight with `4px 4px 0px #121212` drop shadow.