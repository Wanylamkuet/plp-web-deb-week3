# Visual Design Challenge: Budget Tracker

This project is an enhancement of the Budget Tracker application, focusing on visual design, typography, color harmony, and layout structure using CSS.

## Project Structure
* `index.html`: Contains the structural markup for the Budget Tracker, including the header card, expense input form card, and expense table card.
* `style.css`: Contains custom styling rules applying CSS variables, custom typography, form and table layout enhancements, and card-based container styling.
* `README.md`: Explains the design choices, custom CSS implementations, and visual structure.

## Key Design Enhancements

1. **Color Palette:**
   - Background: Light slate gray (`#f4f6f9`) for clean, low-contrast viewing.
   - Cards & Containers: Solid white (`#ffffff`) with subtle light gray borders (`#e2e8f0`).
   - Primary Accent & Buttons: Royal Blue (`#2563eb`) with a dark hover state (`#1d4ed8`).
   - Table Headers: Slate dark (`#1e293b`) for clear differentiation.

2. **Typography:**
   - Google Fonts pairing: **Poppins** (Bold/Semi-bold) for headings and **Inter** (Regular/Medium) for body text, table content, and form inputs.

3. **CSS Box Model & Card Layout:**
   - Every major section (`Header`, `Form`, `Table`) is enclosed in a `.card` wrapper using `margin-bottom`, `padding`, `border-radius: 12px`, and subtle drop shadows (`box-shadow`).

4. **Table & Form Styling:**
   - Alternating row background colors (`:nth-child(even)`) for clear reading line tracking.
   - Padded input fields and buttons with focus/hover transitions.