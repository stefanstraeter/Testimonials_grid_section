# Frontend Mentor - Testimonials Grid Section Solution

This is a solution to the [Testimonials Grid Section Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).  
Frontend Mentor challenges help you improve your coding skills by building realistic, responsive front-end projects.

## Overview

### The Challenge

Users should be able to:

- View an optimized, responsive layout that adapts seamlessly to different screen sizes using CSS Grid and Flexbox

### Links

- **Solution URL:** [GitHub Repository](https://github.com/stefanstraeter/Testimonials_grid_section.git)
- **Live Site URL:** [Live Demo](https://stefanstraeter.github.io/Testimonials_grid_section/)

### Screenshot
<img width="1543" height="946" alt="Testimonials Grid Section" src="https://github.com/user-attachments/assets/9d8b74fe-dd19-4802-9238-b8e1cb4b3c38" />


## My Process

### Built With

- **HTML5** – semantic and accessible structure
- **CSS3** – modern layout techniques using Grid and Flexbox
- **Mobile-First Workflow** – using media queries for progressive enhancement
- **CSS Custom Properties** – for maintainable design tokens
- **CSS Reset** – to ensure consistency across browsers

### Key Features & Techniques

#### Mobile-First Responsive Design

- The layout starts as a single-column stack, ideal for small screens.
- Media queries introduce enhanced grid layouts at larger breakpoints (e.g. `min-width: 768px`).
- The wrapper and body styles adapt spacing and alignment based on screen size.

#### CSS Grid with Template Areas

- Grid structure defined using `grid-template-areas` for clarity and maintainability.
- Layout variations are handled cleanly by naming sections (`daniel`, `patrick`, etc.) and assigning them via CSS.
- Use of `repeat()`, `clamp()`, and `auto` for dynamic column sizing and spacing.

#### Semantic HTML & Accessibility

- Semantic elements like `<section>`, `<header>`, `<h1>`, and `<span>` improve document structure and assistive technology support.
- Descriptive alt text and meaningful hierarchy enhance screen reader compatibility.

#### Theming and Utility Classes

- CSS variables (e.g. `--Grey-100`, `--Purple-500`) provide centralized control over the design system.
- Utility classes like `.text-light` and `.text-dark` promote reuse and clean code.

## Author

- GitHub: [@stefanstraeter](https://github.com/stefanstraeter)
- Frontend Mentor: [@stefanstraeter](https://www.frontendmentor.io/profile/stefanstraeter)
