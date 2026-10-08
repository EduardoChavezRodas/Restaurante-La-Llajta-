---
name: Sabor de la Llajta
colors:
  surface: '#fff8f6'
  surface-dim: '#ebd6d0'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ed'
  surface-container: '#ffe9e4'
  surface-container-high: '#f9e4de'
  surface-container-highest: '#f3ded8'
  on-surface: '#241916'
  on-surface-variant: '#5b403b'
  inverse-surface: '#3a2e2a'
  inverse-on-surface: '#ffede8'
  outline: '#907069'
  outline-variant: '#e4beb6'
  surface-tint: '#b82007'
  primary: '#b51d04'
  on-primary: '#ffffff'
  primary-container: '#d9381e'
  on-primary-container: '#fffcff'
  inverse-primary: '#ffb4a6'
  secondary: '#845400'
  on-secondary: '#ffffff'
  secondary-container: '#ffae32'
  on-secondary-container: '#6c4400'
  tertiary: '#29674c'
  on-tertiary: '#ffffff'
  tertiary-container: '#448064'
  on-tertiary-container: '#f5fff6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad3'
  primary-fixed-dim: '#ffb4a6'
  on-primary-fixed: '#3f0300'
  on-primary-fixed-variant: '#8f1100'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#ffb959'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#643f00'
  tertiary-fixed: '#b1f0ce'
  tertiary-fixed-dim: '#95d4b3'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#0e5138'
  background: '#fff8f6'
  on-background: '#241916'
  surface-variant: '#f3ded8'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  title-dish:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  price-tag:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: -0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

This design system establishes a rustic-chic gastronomic aesthetic celebrating Bolivian culinary heritage ("Tradición boliviana en cada bocado") through contemporary digital craft. The brand balances ancestral kitchen warmth with high-end hospitality elegance.

- **Brand Personality**: Warm, authentic, generous, culinary-focused, and vibrant.
- **Target Audience**: Discerning diners, cultural food enthusiasts, local foodies, and event organizers seeking elevated traditional Cochabambino comfort food.
- **Emotional Response**: Appetite arousal, hospitable warmth, textural richness, and cultural pride.
- **Visual Movement**: Contemporary Editorial Rustic-Chic. Combines rich clay and roasted earth tones, tactile cream surfaces, graceful editorial display typography, and rounded organic card containers mimicking natural ceramic kitchenware.

## Colors

The color palette draws directly from the kitchen: rocoto peppers, charred meats, sweet corn humintas, fresh huacatay, and clay serving platters.

- **Primary (`#D9381E` - Rocoto Terracotta)**: High-impact actions, active badges, highlights, and primary CTA buttons. Conveys fire, chili spice, and hospitality.
- **Secondary (`#E59819` - Llajta Amber Gold)**: Accents, ratings, badges for chef specialties, interactive hovers, and toasted textures.
- **Tertiary (`#2D6A4F` - Huacatay Herb Green)**: Dietary tags (vegetarian, traditional), freshness indicators, and organic culinary certifications.
- **Neutral Dark (`#231815` - Charred Charcoal Umber)**: Primary text, footer backgrounds, and high-contrast structural framing. Replaces clinical black with deep roasted warmth.
- **Canvas / Background (`#FCF9F2` - Warm Ivory Cream)**: Base screen background, reminiscent of stone ground maicena and warm artisanal linen.
- **Surface Elevation (`#FFFFFF`)**: Card surfaces, reservation modals, and floating panels to preserve crisp dish imagery.

## Typography

The type system juxtaposes the culinary romanticism of **Playfair Display** with the clear functional legibility of **Plus Jakarta Sans**.

- **Editorial Headlines**: Reserve Playfair Display for section intros, dish names, and storytelling anchors to impart gastronomic refinement.
- **Functional Interface & Pricing**: Use Plus Jakarta Sans for descriptions, nutritional specs, button labels, and prices to ensure immediate scanning under varying ambient lighting conditions.
- **Hierarchy Rules**: Numerical prices in dish cards utilize `price-tag` with bold tabular weights to pair naturally with Latin currency formats (e.g., "Bs. 65").

## Layout & Spacing

The layout employs a responsive 12-column grid system tailored for visual richness, editorial content, and fast reservation conversion.

- **Breakpoints**: Mobile (< 640px), Tablet (640px – 1024px), Desktop (> 1024px, max canvas width 1280px).
- **Desktop Strategy**: 12-column fluid grid, 24px (`1.5rem`) gutters, and 48px (`3rem`) page margins. Section blocks use `space-xl` for breathing room between gastronomic chapters.
- **Mobile Strategy**: 4-column layout with 16px (`1rem`) gutters and 20px (`1.25rem`) safe canvas margins. Menu tabs and signature plates support horizontal swipe rails with overflowing margins.
- **Rhythm**: Component spacing strictly honors the 4px/8px incremental base, maintaining tight cohesion between dish titles and their ingredient descriptions (`space-xs`), while separating price actions with `space-md`.

## Elevation & Depth

Visual depth is achieved through warm, tinted ambient drop shadows that mirror incandescent dining room lighting rather than generic gray drop shadows.

- **Ambient Cast Shadow**: Shadows employ an amber-charcoal tint (`rgba(35, 24, 21, 0.08)`) with wide dispersion (e.g., `0 12px 32px -4px rgba(35, 24, 21, 0.08)`).
- **Dish Hover State**: Elevation subtly shifts with a physical lift (`translateY(-4px)`) and a warmer terracotta-tinted glow (`rgba(217, 56, 30, 0.14)`).
- **Surface Layering**: Crisp white (`#FFFFFF`) card bodies sit directly atop the warm ivory (`#FCF9F2`) canvas, demarcated by a microscopic hairline border (`rgba(35, 24, 21, 0.06)`) to preserve clean silhouettes without visual clutter.

## Shapes

The design system embraces generous, organic curves reflecting traditional Andean earthenware and wood serving trays.

- **Base Radius (`rounded-lg` / 16px)**: Standard for dish cards, promotional tiles, interactive inputs, and reservation booking pickers.
- **Large Radius (`rounded-xl` / 24px)**: Hero visual cards, modal overlays, story blocks, and photo carousels.
- **Pill Radius (`9999px`)**: Category filter tags, dietary chips, status badges, and primary action buttons.

## Components

### Buttons
- **Primary CTA ("Reservar Mesa" / "Pedir Online")**: Pill-shaped container, solid `#D9381E` background, `#FFFFFF` text, `label-md` uppercase styling, padded with `0.875rem 2rem`. Subtle golden glow on hover with scale transition (1.02).
- **Secondary CTA ("Ver Menú Completo")**: Outlined 1.5px solid `#231815`, transparent fill, `#231815` text. On hover, fills with `#231815` and `#FCF9F2` text.
- **Ghost Button ("Nuestra Historia")**: Text link paired with a terracotta arrow indicator, `#D9381E`, underline appears on hover.

### Food & Dish Cards
- **Structure**: Elevated card (`#FFFFFF`) with 16px–24px border radius.
- **Image Treatment**: 16:10 or 1:1 aspect ratio, overflow hidden, featuring saturated food photography with warm contrast.
- **Badging**: Floated in top-left corner (e.g., "Especialidad de la Casa", "Picante Suave").
- **Content Hierarchy**: Dish name (`title-dish`), rustic ingredient summary (`body-md`), bottom row pairing tabular price (`price-tag` in `#D9381E`) with a compact round add/view button.

### Badges & Dietary Chips
- **Traditional / Chef's Pick**: `#E59819` background at 15% opacity, solid `#231815` text, pill shape.
- **Fresh / Vegetarian**: `#2D6A4F` background at 15% opacity, solid `#2D6A4F` text.
- **Llajwa / Spicy Heat Indicator**: Pill tag with miniature rocoto pepper iconography and terracotta text.

### Category Filter Rail
- Pill selectors with horizontal scroll on mobile. Active tab features solid `#231815` with `#FCF9F2` text; inactive tabs use `#FFFFFF` background with a subtle `#231815`/10% border.

### Inputs & Reservation Form
- Warm ivory container (`#FFFFFF`), 12px padding, 16px corner radius, `#231815` text. Border defaults to 1.5px solid `rgba(35, 24, 21, 0.15)`, transitioning to `#D9381E` on focus with no default browser outline.