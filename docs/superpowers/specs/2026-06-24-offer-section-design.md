# Grid Offer Section Design Specification

## Overview
A 2x2 grid section based on the provided `offer` copy. Following the "Studio Nika" aesthetic, it utilizes sharp edges, thin dividers, and deep structural padding instead of rounded cards or shadows.

## Components
- **Header**: Centered or left-aligned typography showcasing the primary value hook.
- **Grid Layout**:
  - Desktop: 2x2 flat grid (`md:grid-cols-2`).
  - Separated by thin, subtle borders (`border-gray-200`) without container frames for a technical blueprint feel.
  - Mobile: Simple 1-column layout.
- **Grid Cells**:
  - Generous padding (`p-10`).
  - Strong, bold headings.
  - Descriptive copy with highlighted blue link tags.

## Aesthetic Direction
- **Style**: Architect / Technical Grid.
- **Shadows**: None (`shadow-none`).
- **Rounding**: None (`rounded-none`).

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS.
- **Responsive**: Standard responsive configuration transitioning from 1 col on mobile to a structured 2x2 layout on larger screens.
