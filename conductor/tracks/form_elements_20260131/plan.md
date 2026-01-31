# Implementation Plan - Form Elements

Implement a comprehensive set of soft-brutalist form elements (inputs, textareas, selects, checkboxes, radios, and file uploads) according to the `lembrut` design system.

## Phase 1: Foundation & Base Inputs
- [x] Task: Define additional CSS variables for validation colors (pastel red, pastel green) in `src/lembrut.css`. d9855b1
- [x] Task: Implement base styles for `.input`, `.textarea`, and `.select` with thick outlines and solid shadows. 444aae5
- [x] Task: Implement `:focus` and active states (tactile "push down") for base inputs. 0addc59
- [ ] Task: Implement `.label` (bold, uppercase) and `.helper-text` (gray) components.

## Phase 2: Custom Selection Controls
- [ ] Task: Create custom-styled `.checkbox` components using the "fully custom" approach (hiding native input, styling a pseudo-element).
- [ ] Task: Create custom-styled `.radio` components with consistent rounded corners (or circular variant) and thick outlines.
- [ ] Task: Implement `.file-input` wrapper to style the file upload button and field.

## Phase 3: Validation States & Refinement
- [ ] Task: Implement `.is-error` and `.is-success` utility classes for all form elements.
- [ ] Task: Ensure accessibility for custom controls (focus rings, keyboard interaction).
- [ ] Task: Update the demo page (`index.html`) with a comprehensive "Forms" section.
