# Interactive Mobile Contrast Section Specification

## Overview
Optimizes the comparison grid for mobile viewports using an interactive Tab Toggle. Instead of stacking the Red Ocean (Agency) and Blue Ocean (Partner) columns into an endlessly long vertical list, mobile users can switch between the two models with a single tap. On desktop, both columns remain side-by-side in their symmetrical layout.

## Components
- **Tab Selector (Mobile Only)**:
  - Fixed or clean inline toggle with two buttons: "Agencja IT" and "Model Partnerski".
  - Active button is highlighted in blue to guide the user's focus.
- **Content Columns**:
  - Desktop: Standard 2-column comparison table.
  - Mobile: Displays only the selected column's cells, hiding the other.
- **Micro-interactions**: Smooth active state changes on buttons.

## Aesthetic Direction
- **Style**: Interactive technical sheet.
- **Borders**: Razor-thin dividers maintained.
- **Contrast**: Clear distinctions between active/inactive tabs.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, minimal client-side Javascript.
