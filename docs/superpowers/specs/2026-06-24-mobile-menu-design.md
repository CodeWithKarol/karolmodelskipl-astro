# Mobile-First Hamburger Menu Design Specification

## Overview
A minimalist, full-screen mobile navigation panel triggered by a hamburger menu icon.

## Components
- **Hamburger Button**: Visible only on mobile screens, toggles the menu visibility.
- **Overlay Panel**: 
  - `fixed` position, covering the viewport.
  - High `z-index`.
  - White background.
  - Close button ("X") in the top right.
- **Navigation Content**:
  - Vertical list of navigation items.
  - "Oferta" section is **expanded by default**, showing all services and their descriptions.
  - "Baza wiedzy" and "Contact" links clearly placed.

## Aesthetic Direction
- **Whitespace**: Generous padding to maintain an editorial, premium feel.
- **Typography**: Bold, large text for links; smaller, lighter text for descriptions.
- **Interaction**: Smooth fade or slide-in transition.

## Implementation Details
- **Logic**: State-based (or simple Alpine.js/Vanilla JS) to toggle the `hidden` class of the overlay panel.
- **Responsiveness**: The desktop `Header.astro` component will transition to the hamburger layout at a defined breakpoint (e.g., `md:`).

## Success Criteria
- Navigation is fully accessible on mobile devices.
- Design remains consistent with the desktop version (clean, minimalist).
- "Oferta" services are immediately visible when the menu opens.
