---
name: Hyperlocal Professional Exchange
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#001a42'
  on-tertiary-container: '#3980f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  mono-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  container-padding-mobile: 16px
  container-padding-desktop: 40px
  gutter: 24px
  section-gap: 64px
---

## Brand & Style
The design system is anchored in the concept of "Verified Competence." It targets high-value local service providers and discerning clients who prioritize reliability over low cost. The aesthetic is **Corporate / Modern**, characterized by a rigorous adherence to hierarchy, high-density information presented with clarity, and a "Pro" atmosphere that eliminates visual noise.

The emotional response should be one of immediate trust and systemic efficiency. By utilizing expansive whitespace and a structured layout, the UI recedes to let the quality of work and the reputation of the users take center stage.

## Colors
The palette is built on a foundation of **Deep Navy** (#0F172A) to communicate authority and institutional stability. This is balanced by a **Vibrant Success Green** (#10B981) used exclusively for financial triggers, completion statuses, and positive growth metrics to reinforce the feeling of a thriving marketplace.

- **Primary:** Deep Navy for headers, primary buttons, and heavy text.
- **Secondary (Success):** Emerald Green for "Hire," "Payment Complete," and "Active" indicators.
- **Accent:** A corporate blue is reserved for secondary actions and links.
- **Neutrals:** A spectrum of cool grays (Slate) provides the necessary scaffolding for the interface without introducing warmth that might detract from the professional tone.

## Typography
This design system utilizes **Inter** exclusively to leverage its exceptional legibility and systematic feel. The type scale is optimized for high-density data and clear hierarchies.

- **Headlines:** Use tight letter spacing and Bold weights to create a strong visual anchor.
- **Body Text:** Standard weights with generous line heights to ensure long-form project descriptions remain readable.
- **Labels:** Semi-bold weights are used for metadata, status chips, and button labels to ensure they are distinct from body content.

## Layout & Spacing
The layout follows a **12-column fixed grid** on desktop (max-width 1280px) and a fluid single-column layout on mobile. 

- **Grid:** Use a 24px gutter to maintain "breathability" between dense gig cards.
- **Vertical Rhythm:** Built on a 4px baseline. Spacing between elements within a component (e.g., card title to price) should be 8px or 12px. Spacing between components should be 24px or 32px.
- **Safe Areas:** Generous 40px margins on desktop reinforce the premium, "un-crowded" feel of a professional tool.

## Elevation & Depth
Hierarchy is established through **Ambient Shadows** and **Tonal Layers** rather than high-contrast borders.

- **Level 0 (Background):** #F8FAFC (Neutral-50).
- **Level 1 (Cards/Surface):** White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(15, 23, 42, 0.05)).
- **Level 2 (Hover/Active):** Slightly deeper shadow (0px 8px 30px rgba(15, 23, 42, 0.08)) to indicate interactivity.
- **Overlays:** Modals and dropdowns use a crisp 1px border (#E2E8F0) in addition to the Level 2 shadow to ensure separation on white backgrounds.

## Shapes
The design system uses a **Soft (Level 1)** shape language. The 4px (0.25rem) radius for standard elements creates a modern look while maintaining a sense of precision and "sharpness" appropriate for a professional marketplace.

- **Buttons & Inputs:** 4px radius.
- **Gig Cards & Container Modules:** 8px (0.5rem) radius.
- **Status Chips:** Full pill-shape to distinguish them from interactive buttons.

## Components
- **Gig Cards:** Feature a white surface, subtle Level 1 shadow, and a 1px Slate-200 bottom border for the footer section. Use Semi-bold Inter for pricing.
- **Status Trackers:** A horizontal stepper with Success Green nodes for completed phases and Deep Navy for the active phase. Transitions should be smooth and immediate.
- **Buttons:** 
  - *Primary:* Deep Navy background with White text.
  - *Success:* Emerald Green background for final "Hire" or "Pay" actions.
  - *Outline:* 1px Slate-300 border with Deep Navy text.
- **Input Fields:** Minimalist design with a 1px Slate-200 border that shifts to Blue-500 on focus. Labels sit outside the field in Label-MD styling.
- **Real-time Chat:** Messaging bubbles use subtle tonal differences. User messages in Primary Navy (White text), respondent messages in Light Gray (Slate-900 text). Include "Read" receipts and "Typing" indicators in Label-MD.
- **Trust Badges:** Small, circular icons with the Success Green color to indicate "Identity Verified" or "Payment Secured."