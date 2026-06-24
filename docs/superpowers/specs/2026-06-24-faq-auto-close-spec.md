# Auto-Close FAQ Mobile-First Design Specification

## Overview
Enhances the FAQ accordion UX with an "Auto-Close" (One Active Only) behavior. Clicking any collapsed question expands it and automatically closes any previously expanded question. This maintains a compact page length on mobile and keeps the reader focused on one answer at a time.

## Components
- **Accordion Items**:
  - Interactive header button.
  - Collapsible body container.
- **Auto-Close Logic**:
  - When a question is clicked:
    - Check if it is currently expanded.
    - If collapsed, close all other expanded items first (rotating icons back), then open the clicked item.
    - If expanded, simply close it.

## Aesthetic Direction
- **Style**: Fluid, interactive, and neat.
- **Transitions**: Seamless class toggling.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, Javascript.
- **Behavior**: Applies to both desktop and mobile as it is a universal gold standard for interactive FAQs.
