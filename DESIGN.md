---
name: Monochrome Editorial
colors:
  surface: '#faf9f9'
  surface-dim: '#dadada'
  surface-bright: '#faf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f3'
  surface-container: '#efeeed'
  surface-container-high: '#e9e8e8'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#4c4546'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f0f0'
  outline: '#7e7576'
  outline-variant: '#cfc4c5'
  surface-tint: '#5e5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1b'
  on-primary-container: '#848484'
  inverse-primary: '#c6c6c6'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdf'
  on-secondary-container: '#626262'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#838484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c6'
  on-primary-fixed: '#1b1b1b'
  on-primary-fixed-variant: '#474747'
  secondary-fixed: '#e4e2e2'
  secondary-fixed-dim: '#c7c6c6'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#464747'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#faf9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.01em
  body-sm:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
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
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

This design system is built on the principles of **Editorial Minimalism**. It prioritizes content through extreme clarity, generous negative space, and a refined "Product Designer" aesthetic. The personality is sophisticated, confident, and quiet, allowing the work itself to provide the visual narrative.

The aesthetic blends **Modernism** with subtle **Tactile** cues. It uses high-contrast typography to establish hierarchy and thin, low-opacity dividers to maintain structure without clutter. The goal is to evoke a sense of premium craftsmanship and meticulous attention to detail.

## Colors

The palette is strictly monochromatic. By removing hue, we place the emphasis on value, texture, and typography.

- **Primary:** Deep Black (#000000) for core headings and active states.
- **Secondary:** Mid-tone Grays (#666666) for body copy to reduce visual vibration against bright backgrounds.
- **Tertiary:** Ultra-light Gray (#F5F5F5) for subtle container backgrounds and section differentiation.
- **Background:** Pure White (#FFFFFF) serves as the primary canvas to maximize perceived space.

## Typography

The typography strategy uses **Hanken Grotesk** for high-impact display moments, delivering a sharp, contemporary feel. **Inter** provides a highly legible, utilitarian base for body content, ensuring the portfolio remains accessible and professional. 

**JetBrains Mono** is used sparingly for labels, metadata, and "tech" details, adding a layer of technical precision to the editorial layout. Tight letter-spacing on large headings mimics high-end print magazines, while body copy maintains generous leading for a comfortable reading experience.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is "Negative Space as a Feature." Large vertical gaps (`section-gap`) separate distinct thoughts or projects.

- **Desktop:** 64px outer margins with 32px gutters. Content should often be centered or offset to create an asymmetrical, editorial feel.
- **Mobile:** 24px outer margins. Elements stack vertically, but maintaining vertical breathing room is critical to avoid a "cramped" mobile experience.
- **Alignment:** Use a mix of left-aligned text for readability and centered display headers for impact.

## Elevation & Depth

Depth is communicated through **Tonal Layering** and **Ambient Shadows** rather than heavy borders.

- **Base Layer:** The white canvas (#FFFFFF).
- **Surface Layer:** Subtle light gray (#F5F5F5) cards or sections used to group related content.
- **Shadows:** Use a single, highly diffused shadow style: `0 10px 40px rgba(0, 0, 0, 0.04)`. It should look like a soft glow of depth rather than a distinct shadow.
- **Focus:** Interactive elements may use a soft 1px border (#EEEEEE) to define edges against the white background.

## Shapes

The shape language is **Rounded**, balancing the sharp, bold typography with approachable, soft corners. 

Standard components (cards, buttons) use a 0.5rem (8px) radius. Larger containers or feature imagery may use a 1rem (16px) radius to emphasize the "soft-modern" aesthetic. Media (images/video) should always carry the `rounded-lg` or `rounded-xl` tokens to maintain the design system's consistent softness.

## Components

- **Buttons:** Primary buttons are solid black with white text; secondary buttons are transparent with a 1px soft gray border. Use generous horizontal padding (2x the vertical padding).
- **Cards:** Borderless by default. Use the tertiary background color (#F5F5F5) and the ambient shadow token. Content inside should have at least 32px of internal padding.
- **Navigation:** Minimalist text-only links in Inter. The active state is indicated by a weight change (Medium) or a small black dot above the label.
- **Chips/Tags:** Use the `label-mono` typography. Backgrounds should be light gray (#F0F0F0) with no border and high pill-shaped roundedness.
- **Input Fields:** Bottom-border only (1px #DDD) for a classic editorial look, transitioning to black on focus.
- **Media Wrappers:** Images should always include a very subtle 1px inner stroke to ensure light images don't bleed into the white background.