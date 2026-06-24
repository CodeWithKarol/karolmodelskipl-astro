# Contrast Section Design Specification

## Overview
A minimalist 2-column comparative table inspired by the "Studio Nika" aesthetic, mapping out the contrasts between traditional IT agencies and the Partner model using the `contrast` copy.

## Components
- **Header**: Large typography emphasizing the value shift ("Twoja firma zasługuje na eksperta IT...").
- **Table Structure**:
  - Two major columns: Left ("Zwykły Wykonawca / Agencja IT") and Right ("Model Partnerski").
  - The right column is subtly highlighted (e.g., using `bg-blue-50/40` or distinct text accents) to visually guide the user's preference.
  - Razor-thin lines separating each of the 4 rows (`border-b border-gray-100`).
- **Cells**:
  - Left Cell: Red Ocean downsides (Muted gray or soft red-tint indicator).
  - Right Cell: Blue Ocean upsides (Stronger text contrast, blue or green-tint indicator).

## Aesthetic Direction
- **Style**: Symmetrical Flat Table.
- **Borders**: Sharp edges, no rounded corners, no shadows.
- **Whitespace**: Spacious rows with comfortable reading distances.

## Implementation Details
- **Tech Stack**: Astro component, Tailwind CSS.
- **Responsiveness**: Stacks beautifully into individual grouped rows on mobile (Red item, followed directly by its corresponding Blue alternative) to maintain contrast without narrowing the text boxes.
