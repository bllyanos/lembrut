# Tech Stack: lembrut

## Framework Core
- **CSS (Vanilla)**: Primary language for the framework, utilizing modern features like CSS Variables (Custom Properties) for theme customization.
- **PostCSS**: Used for CSS transformations and optimizations.
  - **Autoprefixer**: To ensure cross-browser compatibility by adding necessary vendor prefixes.
- **Vite**: The build tool and development server, chosen for its speed and efficient hot module replacement.

## Layout Engine
* **Approach**: Hybrid (Flexbox 12-column + CSS Grid Utilities)
* **Breakpoints**: 
  * Tablet: `768px`
  * Desktop: `1024px`
* **Spacing**: Variable-based 1-16 scale.

## Documentation & Demo
- **HTML5**: For the structure of the demo and documentation pages.
- **JavaScript (Vanilla)**: For any lightweight interactive components or demo-specific logic.

## Deployment & Distribution
- **NPM**: For package management and distribution of the framework.