# Asymmetric Story Section Design Specification

## Overview
An asymmetric, editorial-grade "Story" section based on Russell Brunson's "Epiphany Bridge" framework. It separates the author's backstory and industry problem from the modern mission using a dynamic two-column split layout.

## Components
- **Layout**: Asymmetric 2-column split (60/40 grid or flex container on desktop, stacked on mobile).
- **Left Column (60%): Backstory & Problem**
  - Section Badge: "Moja Historia".
  - Large display headline.
  - Large-scale introductory text with internal links highlighted in blue.
  - Problem subtitle and structural body copy with ample line-height.
- **Right Column (40%): The Mission & Solution**
  - Contained inside a minimalist card with subtle background tint (`bg-gray-50`) and a thin border.
  - Section Badge: "Moja Misja".
  - Core mission statements with emphasis on enterprise standards and AI efficiency.

## Aesthetic Direction
- **Style**: Editorial / Narrative-driven.
- **Borders**: Sharp edges (`rounded-none`), thin lines.
- **Whitespace**: Drastic vertical padding (`py-28`) for visual breathing room.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS.
- **Responsiveness**: Standard responsive grid/flex layout (stacking on smaller screens).
