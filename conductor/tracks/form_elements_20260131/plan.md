# Implementation Plan - Form Elements

Implement a comprehensive set of soft-brutalist form elements (inputs, textareas, selects, checkboxes, radios, and file uploads) according to the `lembrut` design system.

## Phase 1: Foundation & Base Inputs [checkpoint: cb7bbad]
- [x] Task: Define additional CSS variables for validation colors (pastel red, pastel green) in `src/lembrut.css`. d9855b1
- [x] Task: Implement base styles for `.input`, `.textarea`, and `.select` with thick outlines and solid shadows. 444aae5
- [x] Task: Implement `:focus` and active states (tactile "push down") for base inputs. 0addc59
- [x] Task: Implement `.label` (bold, uppercase) and `.helper-text` (gray) components. 77d6593

## Phase 2: Custom Selection Controls
- [x] Task: Create custom-styled `.checkbox` components using the "fully custom" approach (hiding native input, styling a pseudo-element). d6af05a
- [x] Task: Create custom-styled `.radio` components with consistent rounded corners (or circular variant) and thick outlines. 2112638
- [x] Task: Implement `.file-input` wrapper to style the file upload button and field. 6be70be

## Phase 3: Validation States & Refinement
- [x] Task: Implement .is-error and .is-success utility classes for all form elements. 94c6fe0
- [x] Task: Ensure accessibility for custom controls (focus rings, keyboard interaction). defed9f
- [ ] Task: Update the demo page (`index.html`) with a comprehensive "Forms" section.
