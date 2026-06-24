# Interactive Mobile Story Section Specification

## Overview
Optimizes the narrative-rich "Story" section for mobile devices. On mobile screens, it limits the backstory to a teaser and hides the long problem description behind an interactive "Read more" toggle, preventing extreme page length and cognitive fatigue while keeping desktop layouts fully open.

## Components
- **Layout**:
  - Desktop: Asymmetric 2-column layout (60/40), fully open.
  - Mobile: Single column. Only `intro_text` (the hook) is visible initially.
- **Toggle Button (Mobile only)**:
  - Text: "Czytaj całą historię" with a down arrow.
  - Action: Unveils the rest of the backstory and the problem section (`problem_title` and `problem_text`) on click, then hides itself.
- **Mission Box**: Remains fully visible at the bottom of the section on mobile to ensure the call to action and value proposition are always reachable.

## Aesthetic Direction
- **Style**: Interactive Editorial.
- **Transitions**: Smooth slide/fade when the content is expanded.

## Implementation Details
- **Tech Stack**: Astro, Tailwind CSS, lightweight vanilla JS for the click event.
