# lembrut

**lembrut** (Indonesian: *lembut* / soft + *brutalism*) is a lightweight, soft-brutalist CSS framework. It bridges the gap between raw, structural honesty and approachable, gentle aesthetics.

---

## 🎨 The Aesthetic
Lembrut is defined by high-contrast, tactile interfaces that don't feel "harsh":
- **Soft Palette**: Pastel-driven backgrounds and subtle highlights.
- **Bold Structure**: Thick black outlines and solid, unblurred shadows.
- **Reactive UI**: High-tactility focus and active states that simulate physical interaction.
- **Friendly Edges**: Consistent, generous rounded corners on every component.

## 🚀 Quick Start

### Installation
```bash
npm install lembrut
```

### Basic Usage
Include the stylesheet in your project and start building with soft-brutalist components:

```html
<link rel="stylesheet" href="src/lembrut.css">

<!-- A soft brutalist card -->
<div class="card p-8 bg-pastel-yellow">
  <h1 class="text-4xl font-black mb-4">Hello Lembrut</h1>
  <p class="mb-6">Building bold interfaces with a gentle touch.</p>
  <button class="btn btn-primary">Get Started</button>
</div>
```

## 🛠 Features

### 1. Hybrid Grid System
Choose between a classic 12-column Flexbox grid or modern CSS Grid utilities:
```html
<div class="row gap-4">
  <div class="col-6">Half Width</div>
  <div class="col-6">Half Width</div>
</div>

<div class="grid grid-cols-3 gap-6">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div>
```

### 2. Comprehensive Typography
A full scale of typography utilities from `text-6xl` to `text-sm`, paired with font-weights from `font-black` (900) to `font-normal` (400).

### 3. Tactile Components
Buttons, inputs, selects, checkboxes, and radios—all featuring reactive "push-down" effects on click and focus.

## 📖 Documentation
Lembrut comes with a built-in, documentation-style showcase. To see all components, colors, and layout systems in action:

1. Clone the repo
2. Run `npm install`
3. Run `npm run dev`
4. Open `index.html` in your browser

## 🏗 Development

Lembrut is built with **Vanilla CSS**, **PostCSS**, and **Vite**.

- **Dev Server**: `npm run dev`
- **Build**: Optimized with Autoprefixer for cross-browser support.

---

## 📄 License
Licensed under the ISC License.