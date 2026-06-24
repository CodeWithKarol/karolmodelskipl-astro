# Studio Nika Mobile-First Swipe Social Proof Specification

## Overview
Optimizes the "Trusted By" (Studio Nika style) section for mobile screens using a touch-friendly, horizontal scrollable/swipeable track. This saves valuable vertical space on phones while maintaining the precise, architectural grid line style. On desktop, it restores the flat 4-column layout.

## Components
- **Layout**:
  - Desktop (`md` and up): Standard flat 4-column grid with subtle borders between columns.
  - Mobile (under `md` breakpoint): Horizontal flex layout (`flex overflow-x-auto snap-x snap-mandatory scrollbar-none`) allowing users to swipe through cards in a single row.
- **Borders & Dividers**:
  - Mobile: Thin vertical borders (`border-r border-gray-200`) separating the swipable cards.
  - Desktop: Sharp horizontal/vertical lines dividing columns.
- **Card Sizing on Mobile**:
  - Fixed width (e.g., `w-[280px]` or `w-4/5`) to ensure a teaser of the next card is visible, inviting the swipe gesture.
  - `snap-start` or `snap-center` behavior for clean sliding stops.

## Aesthetic Direction
- **Style**: Studio Nika (architectural blueprint with precise lines).
- **Whitespace**: Minimal padding vertically on mobile, spacious on desktop.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS (no external JS needed, using pure CSS snap points and flex properties).
