# Interactive Mobile Offer Section Specification

## Overview
Optimizes the narrative-heavy "Offer" section for mobile viewports using collapsible accordions, providing a consistent interactive layout with the "Impact" section. On desktop, the component gracefully displays its original open 2x2 grid.

## Components
- **Layout**:
  - Desktop: Standard open 2x2 grid.
  - Mobile: Single-column vertically stacked accordion.
- **Accordion Trigger (Mobile Only)**:
  - Contains index numbers (`01`, `02`, `03`, `04`), title, and a rotating plus/minus icon.
- **Accordion Content**:
  - Contains description copy with embedded active blue link tags.
  - Hidden on load on mobile viewports; always visible on desktop viewports.

## Aesthetic Direction
- **Style**: Cohesive interactive blueprint-style grid.
- **Visual Feedback**: Soft toggle state shifts and intuitive icons.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, lightweight vanilla JS for the click events.
