# Product Guidelines: lembrut

## Design Philosophy: Soft Brutalism
Lembrut balances the raw, structural honesty of brutalism with a "soft" approachability. This is achieved through the interplay of bold geometric boundaries and gentle visual properties.

## Visual Identity

### 1. The "Soft" Definition
- **Rounded Corners**: Every element must feature noticeably rounded corners (consistent `border-radius`). Avoid sharp, square-ish edges.
- **Pastel Palette**: Use a high-lightness, low-saturation colorscheme to provide a gentle background for bold content.
- **Grayscale Balance**: While black is used for structure, use 40% gray for inactive elements or to soften non-primary structural lines.

### 2. The "Brutalist" Structure
- **Consistent Thickness**: All outlines must use a uniform `border-width` (e.g., 3px) across all components to create a unified, sturdy feel.
- **Generous Negative Space**: Maintain large padding and margins. Bold lines require significant whitespace to avoid visual clutter and maintain clarity.
- **Solid Shadows**: Shadows must be solid blocks (no blur) that simulate physical depth.

### 3. Interactive Motion
- **Tactile Feedback**: Interactive elements should simulate a physical "push down" effect. When clicked, elements should translate by the shadow offset, making the element appear to move into the shadow's space.

## Implementation Principles
- **Clarity First**: Ensure that even with soft colors, the hierarchy is established through bold outlines.
- **Customizability**: Expose core properties (radius, border-width, shadow-offset) as CSS variables for easy user adjustment.