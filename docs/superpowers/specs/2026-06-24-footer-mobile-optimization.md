# Mobile-First Footer Design Specification

## Overview
Optimizes the 4-column architectural footer for mobile-first user experience. To prevent excessive vertical scrolling on phones, Column 3 ("Rozwiązania dla firm") and Column 4 ("Dlaczego Model Elite?") are placed side-by-side in a 2-column sub-grid on mobile, while Columns 1 and 2 remain stacked. Divider borders are updated responsively.

## Components
- **Layout**:
  - Desktop: Symmetrical 4-column open grid separated by thin vertical dividers (`md:border-r border-gray-100`).
  - Mobile: 
    - Column 1 and 2 stacked (full-width), separated by thin horizontal dividers (`border-b border-gray-100`).
    - Column 3 and 4 rendered side-by-side (`grid grid-cols-2 gap-4 pt-8`) to minimize page length.
- **Visuals**:
  - Consistent padding scales responsive to screen size.
  - Links are sized for optimal touch interaction (comfortably spaced lists).

## Aesthetic Direction
- **Style**: Organized, neat architectural grid.
- **Borders**: Adaptive border lines that match the screen topology.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS grid rules.
