# Interactive Asymmetric FAQ Section Specification

## Overview
An editorial-grade, asymmetrical FAQ section. On desktop, the header and subtitle sit on the left (occupying 4 columns), while the interactive accordion list sits on the right (occupying 8 columns). On mobile, it stacks cleanly into a single vertical sequence of accordions.

## Components
- **Layout**: 12-column grid (`lg:grid-cols-12`).
- **Left Column (40%)**: Sticky/static section title and subtitle ("Najczęściej Zadawane Pytania").
- **Right Column (60%)**: A clean vertical list of FAQ items divided by thin borders (`border-b border-gray-100`).
- **Accordions**:
  - Interactive headers that toggle the expansion of the answer paragraph below.
  - Custom chevron or indicator that rotates dynamically on active states.
  - Answers hidden by default (`hidden`) and revealed using client-side vanilla JS.

## Aesthetic Direction
- **Style**: Sophisticated Asymmetry.
- **Borders**: Sharp edges, razor-thin gray divider lines.
- **Contrast**: Deep black headers and slate-gray bodies on white backgrounds.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS, Vanilla JS.
