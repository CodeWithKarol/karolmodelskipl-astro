# Asymmetric Final CTA Section Specification

## Overview
A conversion-focused, asymmetric final CTA section inspired by modern SaaS landing pages. It presents a free IT diagnostic audit (Value: 600 PLN) using a 2-column layout (Benefits on the left, an prominent soft CTA action box on the right). It maps directly to the `/#kontakt` anchor linked in the site navigation.

## Components
- **Anchor**: Configured with `id="kontakt"`.
- **Layout**: 12-column grid (`lg:grid-cols-12`).
- **Left Column (60%): The Value Proposition**
  - Section Badge: "Bezpłatna Diagnoza".
  - Massive, elegant headline.
  - Subtitle introducing the diagnostic process.
  - Beautiful vertical list showing the 3 bullets and their monetary values (e.g., `300 zł`, `200 zł`, `100 zł`) highlighted in blue.
- **Right Column (40%): The Focus Box**
  - Styled as a minimal, flat card with a soft background tint (`bg-blue-50/20`) and thin border.
  - Heading explaining the meeting pack details.
  - Prominent, large-format soft button ("Odbierz Pakiet o Wartości 600 zł za Darmo") that triggers the action.

## Aesthetic Direction
- **Style**: Symmetrical Flat Editorial.
- **Borders**: Sharp edges, no rounded corners, thin dividers.
- **Colors**: Soft blue accents to create contrast and encourage conversion.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS.
