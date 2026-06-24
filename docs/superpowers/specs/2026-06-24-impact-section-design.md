# Asymmetric Impact Section Design Specification

## Overview
A high-end, asymmetric "Impact/Highlights" section based on the provided `impact` content. Designed to explain the business value of professional IT development through a modern split layout (Text on the left, benefit list on the right).

## Components
- **Layout**: Asymmetric 12-column grid (5 columns for header/subheading, 7 columns for benefits on desktop; stacked single-column on mobile).
- **Left Column (40%): Context & Promise**
  - High-impact header: "Standardy Korporacyjne, Które Przejmujesz".
  - Supporting narrative text focusing on ROI and business value.
- **Right Column (60%): Detailed Benefits List**
  - Features listed vertically, separated by razor-thin gray lines (`border-t border-gray-100`).
  - Each item includes a bold title, an elegant icon/indicator, and explanatory copy.

## Aesthetic Direction
- **Style**: Ultra-clean, editorial.
- **Borders**: Sharp edges, thin line dividers.
- **Contrast**: Dark slate text on pure white / light gray backgrounds.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS.
- **Responsiveness**: Flex/grid configurations that stack naturally on mobile viewports.
