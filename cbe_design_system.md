---
name: "CBE — UCHS Program Design System"
description: "A dynamic, editorial, and tech-forward design system blending deep midnight tones, electric lime accents, and soft indigo highlights for the CBE educational program."
---

## Overview

CBE (UCHS Program) connects students with real-world learning, career exploration, hands-on experience, and professional networking. The design combines modern editorial craft, tech minimalism, bold asymmetric layouts, bento grid structures, and electric high-contrast accents. It rejects dry institutional tropes in favor of an energetic digital agency feel tailored for forward-looking students.

- **Audience:** High school and pre-college students looking to unlock practical career pathways and real-world skills.
- **Tone & Mood:** Youthful, ambitious, polished, vibrant, and accessible.
- **Design Philosophy:** Bold contrasts, oversized expressive type, authentic student photography, and tactile microinteractions.

## Colors

The color palette centers around **Midnight Navy** and **Deep Navy** dark foundations contrasted with crisp **Off-white** and bright **White** surfaces, brought to life with an energetic **Lime Green** primary accent and thoughtful **Soft Indigo** highlights.

- **Lime Green:** The driving high-energy accent for primary calls-to-action, key badges, and marquee highlights.
- **Midnight Navy:** Ground dark surface for hero, journey, and footer zones.
- **Deep Navy:** Secondary elevated dark surface.
- **Soft Indigo:** Editorial secondary accent for key typographic highlights and category markers.
- **Off-white:** Warm, readable light ground for daylight content sections.

```yaml
colors:
  midnight-navy: "#0B1020"
  deep-navy: "#121B30"
  off-white: "#F5F6F2"
  lime-green: "#C9F36B"
  soft-indigo: "#7584FF"
  white: "#FFFFFF"
  card-lila: "#E8E7FA"
  card-lime: "#EAF9D2"
  card-gray: "#F0F2EB"
  light:
    primary: "#0B1020"
    on-primary: "#FFFFFF"
    surface: "#F5F6F2"
    on-surface: "#0B1020"
  dark:
    primary: "#C9F36B"
    on-primary: "#0B1020"
    surface: "#0B1020"
    on-surface: "#FFFFFF"
```

## Typography

The typographic system pairs the expressive, architectural geometry of **Space Grotesk** for display headlines, numbers, buttons, and editorial motifs with the clarity and legibility of **DM Sans** for all narrative, navigation, and explanatory copy.

```yaml
typography:
  display-xl:
    fontFamily: "Space Grotesk"
    fontSize: 72px
    fontWeight: 700
    lineHeight: 76px
    letterSpacing: -2px
  display-xl-mobile:
    fontFamily: "Space Grotesk"
    fontSize: 32px
    fontWeight: 700
    lineHeight: 36px
    letterSpacing: -1px
  display-lg:
    fontFamily: "Space Grotesk"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 60px
    letterSpacing: -1.5px
  display-lg-mobile:
    fontFamily: "Space Grotesk"
    fontSize: 30px
    fontWeight: 700
    lineHeight: 34px
    letterSpacing: -0.75px
  headline-xl:
    fontFamily: "Space Grotesk"
    fontSize: 44px
    fontWeight: 700
    lineHeight: 48px
    letterSpacing: -1px
  headline-xl-mobile:
    fontFamily: "Space Grotesk"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 32px
    letterSpacing: -0.5px
  headline-lg:
    fontFamily: "Space Grotesk"
    fontSize: 36px
    fontWeight: 600
    lineHeight: 42px
    letterSpacing: -0.5px
  headline-lg-mobile:
    fontFamily: "Space Grotesk"
    fontSize: 24px
    fontWeight: 600
    lineHeight: 30px
    letterSpacing: -0.25px
  headline-md:
    fontFamily: "Space Grotesk"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: -0.5px
  headline-md-mobile:
    fontFamily: "Space Grotesk"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 26px
    letterSpacing: -0.25px
  headline-sm:
    fontFamily: "Space Grotesk"
    fontSize: 22px
    fontWeight: 600
    lineHeight: 28px
    letterSpacing: 0px
  body-lg:
    fontFamily: "DM Sans"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0px
  body-md:
    fontFamily: "DM Sans"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0px
  body-sm:
    fontFamily: "DM Sans"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0px
  label-lg:
    fontFamily: "Space Grotesk"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 20px
    letterSpacing: 0.5px
  label-md:
    fontFamily: "Space Grotesk"
    fontSize: 13px
    fontWeight: 700
    lineHeight: 18px
    letterSpacing: 1px
  label-sm:
    fontFamily: "Space Grotesk"
    fontSize: 11px
    fontWeight: 700
    lineHeight: 16px
    letterSpacing: 1.5px
```

## Layout & Spacing

Desktop layouts are bounded by a centered 1190px container (`max-w-[1190px] mx-auto px-6 md:px-8`) with asymmetrical multi-column splits and bento grids. Mobile viewports collapse into stacked vertical flows while preserving generous tap zones and visual impact.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  section-sm: 48px
  section-md: 80px
  section-lg: 112px
  page-margin: 24px
```

## Elevation & Depth

Layered depth is established through deep multi-layer ambient drop shadows on dark cards, frosted glass surfaces (`backdrop-blur-md`), and radial violet background gradients. Bento cards hover with a smooth 7px translateY lift and expanded diffused ambient shadow.

## Shapes

Shapes feature confident, generous curvatures. Bento cards use a distinct 22px border radius. Buttons and interactive chips use pill shapes (`rounded-full`) or responsive geometric curves.

```yaml
rounded:
  sm: 6px
  DEFAULT: 12px
  md: 16px
  lg: 20px
  bento: 22px
  xl: 28px
  full: 9999px
```

## Motion & Micro-interaction

Motion is rhythmic, fluid, and intentional:
- **Scroll Reveal:** Elements emerge with an upward 25px offset and opacity transition over 750ms.
- **Marquee:** Horizontal ticker smoothly translates at continuous 27s cycle.
- **Scroll Progress:** High-contrast lime green bar at the top edge tracks scroll percentage.
- **Interactive Lift:** Buttons elevate 2-3px on hover; bento cards elevate 7px with increased shadow depth.
- **Reduced Motion:** All transitions honor `prefers-reduced-motion: reduce`.

```yaml
motion:
  state-change:
    duration: 200ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 750ms
    delay: 0ms
    timingFunction: cubic-bezier(0.16, 1, 0.3, 1)
  hover-lift:
    duration: 250ms
    delay: 0ms
    timingFunction: cubic-bezier(0.2, 0, 0, 1)
```

## Voice & Content Strategy

- **Tone:** Direct, inspiring, empowering, clear, authentic.
- **Copy Standards:** All public copy in English. Clear active verbs (`Explore CBE`, `Get Started`, `Take Action`).
- **Student-Centric:** Focus on actionable opportunities, agency, and discovery rather than bureaucratic prerequisites.
