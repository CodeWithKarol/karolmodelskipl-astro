# Studio Nika Style Social Proof Specification

## Overview
A hyper-minimalist, editorial-grade logo and social proof grid inspired by the "Studio Nika" aesthetic. It moves away from standard modern card styles (rounded corners, shadows) and instead uses an "open-border grid" made of razor-thin lines, spacious layouts, and high-end typography.

## Components
- **Container**: Minimal spacing, using an asymmetrical or clean symmetric grid.
- **Grid Structure**:
  - `grid grid-cols-1 md:grid-cols-4`.
  - Grid cells separated by a subtle, thin gray border (`border-gray-200`) representing a "technical spreadsheet" or architectural blueprint.
  - Border logic configured so that cell walls align perfectly without double-thickness lines.
- **Typography & Content**:
  - Large, bold brand names.
  - Small, high-contrast category labels in uppercase tracking.
  - Explanatory context text in highly legible, muted gray.

## Aesthetic Direction
- **Style**: Studio Nika (Ultra-minimalism, editorial, architectural).
- **Structure**: Rounded corners removed (`rounded-none`), shadows removed (`shadow-none`).
- **Dividers**: Clean, flat border lines dividing each client cell.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS.
- **Classes**: Tailwind's `border-r`, `border-b`, `border-t`, `border-l` mapped dynamically or statically to ensure a clean grid look without outer container borders (an "open edge" table).
