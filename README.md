# Bonfire Consulting Website Prototype

Static homepage prototype for Bonfire Consulting. This file set is intended to establish the visual direction, homepage content structure, navigation behavior, and reusable section patterns before the site is recreated in WordPress with Elementor.

## Preview

Open `index.html` directly in a browser.

No build step, package install, or local server is required.

## Files

- `index.html` - Homepage markup, navigation, sections, footer, and small interaction scripts.
- `styles.css` - Global design tokens, responsive layout, section styling, cards, buttons, navigation, and footer styles.
- `assets/` - Logo, video, placeholder/client logos, and section imagery.

## Current Sections

- Header and primary navigation
- Hero section with video, quote card, CTAs, and fire canvas background
- Trusted logo carousel
- Why organizations choose Bonfire
- Solutions card grid
- How organizations engage Bonfire
- Tools and assessments
- Meet Andrew Harrison
- Footer with navigation, contact details, and legal links

## Elementor Translation Notes

The prototype is structured to map cleanly to Elementor:

- Sections map to Elementor sections or containers.
- `.site-container` maps to constrained inner containers.
- Cards, buttons, lists, quote cards, and nav groups are reusable component patterns.
- Colors, spacing, typography, radius, and shadow values are centralized in `:root` inside `styles.css`.
- Comments in the HTML and CSS identify major Elementor mapping areas.

## Design Direction

The visual direction is clean, light, warm, and professional, using Bonfire-inspired orange/gold accents with plum/charcoal text, generous spacing, rounded edges, and restrained shadows.

## Notes

This is a static prototype only. Links currently use placeholder `#` destinations and should be connected during the WordPress/Elementor build.
