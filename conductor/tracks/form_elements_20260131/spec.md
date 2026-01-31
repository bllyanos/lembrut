# Specification: Form Elements (Track: form_elements_20260131)

## Overview
This track introduces a comprehensive set of form components to the `lembrut` framework. These elements will strictly adhere to the "soft brutalist" aesthetic: thick outlines, solid shadows, pastel accents, and tactile interactive states.

## Functional Requirements
- **Core Input Styles**:
  - Implement `input[type="text"]`, `input[type="password"]`, `input[type="email"]`, and `textarea`.
  - Implement `select` dropdown menus.
  - Implement `input[type="file"]` with a custom-styled button.
- **Custom Selection Controls**:
  - Create fully custom-styled `checkbox` and `radio` buttons.
  - Ensure they support `:checked` states using pastel colors (e.g., Pink or Blue).
- **Labels & Validation**:
  - `.label`: Bold, uppercase, positioned above elements.
  - `.helper-text`: 40% gray text below elements for metadata.
  - `.is-error`: Changes outline/shadow to pastel red.
  - `.is-success`: Changes outline/shadow to pastel green.
- **Interactive States**:
  - Focus: Maintain thick black outlines with enhanced solid shadows or color shifts that match the "push down" aesthetic.
  - Active/Click: Elements should translate (translate(2px, 2px)) to simulate a physical press.

## Non-Functional Requirements
- **Accessibility**: Ensure custom checkboxes/radios remain keyboard-navigable and screen-reader friendly.
- **Consistency**: Use existing CSS variables for border-radius, border-width, and shadow offsets.

## Acceptance Criteria
- [ ] All form elements match the visual weight of existing buttons/cards.
- [ ] Error and success states are clearly distinguishable via pastel color shifts.
- [ ] Checkboxes and radio buttons are fully styled and functional across modern browsers.
- [ ] The demo page (`index.html`) is updated with a "Forms" section showcasing all variations.

## Out of Scope
- Complex form logic or validation scripts (this is a CSS-only track).
- Multi-select search components or date pickers.
