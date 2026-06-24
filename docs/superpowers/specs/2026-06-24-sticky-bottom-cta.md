# Sticky Bottom Conversion Float Design Specification

## Overview
Implements an elegant, conversion-focused "Sticky Bottom CTA Button" on mobile devices. When the user scrolls past the initial Hero fold, a subtle, responsive floating action bar slides up from the bottom of the viewport, prompting them to instantly claim their free 600 PLN diagnostic audit. Tapping it smoothly scrolls them down to the final booking section (`#kontakt`).

## Components
- **Floating Button (Mobile Only)**:
  - `fixed bottom-4 left-4 right-4 z-[40]`.
  - Minimal style matching the soft CTA theme (`bg-blue-600 text-white font-bold py-3.5 px-6 rounded-full shadow-xl`).
  - Slide-in transition on activation.
- **Scroll Behavior**:
  - Automatically hidden at the very top (within the Hero fold) to keep the layout extremely clean.
  - Revealed as soon as the user starts exploring downstream sections.
  - Smooth scroll animation targeting `#kontakt`.

## Aesthetic Direction
- **Style**: Lightweight, high-conversion floating element.
- **Micro-animations**: Smooth slide-up transition using CSS `transform` and opacity.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, lightweight client-side scroll listener.
