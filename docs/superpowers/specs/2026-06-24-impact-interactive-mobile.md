# Interactive Mobile Impact Section Specification

## Overview
Optimizes the "Impact" section for mobile-first user experience. On mobile screens, it wraps the detailed benefit descriptions into clean, collapsible accordion panels, enabling users to scan all value propositions immediately. On desktop, the section expands to its original open, asymmetric 2-column layout.

## Components
- **Layout**:
  - Desktop: Asymmetric 2-column layout. Left has the heading and introduction; right has vertical lists of benefits fully open.
  - Mobile: Single column. Each benefit becomes an interactive accordion.
- **Accordion Logic (Mobile Only)**:
  - Header: Contains the numbers (`01`, `02`, `03`) and the benefit title, functioning as a toggle button.
  - Toggle indicator: A small plus/minus or chevron icon that rotates/morphs when active.
  - Body: Contains the description, hidden by default (`hidden` on mobile, but `block` on desktop).

## Aesthetic Direction
- **Style**: Interactive, precise.
- **Feedback**: Immediate visual toggle state shifts.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, lightweight vanilla Javascript for toggle state management.
