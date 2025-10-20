# Design System Style Guide

A comprehensive, modern design system for building consistent and accessible web applications. This style guide documents colors, typography, text styles, buttons, and spacing guidelines to ensure visual coherence across all projects.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage Guidelines](#usage-guidelines)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## 🎨 Overview

This design system serves as a single source of truth for design decisions, providing:
- A documented color palette with usage guidelines
- Typography hierarchy with three font families
- Predefined text styles for common HTML elements
- Button components for different actions
- A spacing scale for consistent layouts
- Responsive design principles

## ✨ Features

- **CSS Variables**: Easy theme customization using CSS custom properties
- **BEM Naming Convention**: Maintainable and scalable CSS architecture
- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **Accessibility**: ARIA labels, focus indicators, and reduced motion support
- **Semantic HTML**: Proper use of HTML5 semantic elements
- **Google Fonts Integration**: Professional typography with Inter, Playfair Display, and Fira Code
- **Interactive Components**: Hover effects and smooth transitions
- **Print Styles**: Optimized for printing documentation

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML and CSS

### Installation

1. **Clone or download** this repository to your local machine

2. **Project files**:
   ```
   design-system/
   ├── index.html
   ├── styles.css
   └── README.md
   ```

3. **Open the project**:
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

### Quick Start

```bash
# If using VS Code with Live Server extension
1. Open the project folder in VS Code
2. Right-click on index.html
3. Select "Open with Live Server"
```

## 📁 Project Structure

```
design-system/
│
├── index.html          # Main HTML document with all components
├── styles.css          # Complete stylesheet with CSS variables
└── README.md          # Project documentation (this file)
```

### File Descriptions

- **index.html**: Contains the complete design system documentation including colors, typography, text styles, buttons, and spacing guidelines. Features semantic HTML with ARIA labels for accessibility.

- **styles.css**: Organized stylesheet with:
  - CSS variables for easy customization
  - BEM naming convention
  - Responsive breakpoints
  - Accessibility features
  - Print styles

## 📖 Usage Guidelines

### Colors

The design system includes six primary colors:

- **Primary Purple** (`#667eea`): Main brand color for buttons and links
- **Deep Violet** (`#764ba2`): Secondary color for accents
- **Success Green** (`#48bb78`): Positive actions and success messages
- **Alert Red** (`#f56565`): Errors and destructive actions
- **Light Gray** (`#edf2f7`): Backgrounds and subtle divisions
- **Dark Slate** (`#1a202c`): Primary text color

### Typography

Three font families are used:

1. **Inter**: Body text and UI elements
2. **Playfair Display**: Headings and titles
3. **Fira Code**: Code snippets and technical content

### Text Styles

Six predefined text styles:

- **H1**: Main page titles (3.5rem, Playfair Display)
- **H2**: Section headings (2.5rem, Playfair Display)
- **H3**: Subsection headings (1.5rem, Inter)
- **Paragraph**: Body text (1rem, Inter)
- **Links**: Interactive text with hover states
- **Code**: Inline code snippets with monospace font

### Buttons

Four button variants:

- **Primary**: Main call-to-action buttons
- **Secondary**: Alternative actions
- **Success**: Confirmations and positive actions
- **Danger**: Destructive actions (delete, cancel)

### Spacing Scale

Six spacing values for consistent layouts:

- **XS** (4px): Tight spacing
- **SM** (8px): Small gaps
- **MD** (16px): Default spacing
- **LG** (24px): Section padding
- **XL** (32px): Major sections
- **XXL** (48px): Hero sections

## 🎨 Customization

### Modifying Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --color-primary: #667eea;    /* Change to your brand color */
    --color-secondary: #764ba2;   /* Secondary brand color */
    /* ... more variables */
}
```

### Changing Fonts

1. Replace Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;700&display=swap" rel="stylesheet">
```

2. Update CSS variables in `styles.css`:
```css
:root {
    --font-primary: 'YourFont', sans-serif;
}
```

### Adjusting Spacing

Modify spacing scale in CSS variables:

```css
:root {
    --spacing-xs: 4px;
    --spacing-sm: 8px;
    /* Adjust as needed */
}
```

## 🌐 Browser Support

This design system supports all modern browsers:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

**Note**: CSS Grid and CSS Variables are used, which are not supported in IE11.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above (default)
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px

## ♿ Accessibility Features

- Semantic HTML5 elements
- ARIA labels for screen readers
- Keyboard navigation support
- Focus indicators for interactive elements
- Reduced motion support for users who prefer it
- Proper color contrast ratios

## 🔧 Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Google Fonts (Inter, Playfair Display, Fira Code)

## 💡 Future Enhancements

Potential additions to the design system:

- [ ] Form elements (inputs, textareas, selects)
- [ ] Card components
- [ ] Alert/notification components
- [ ] Modal dialogs
- [ ] Navigation bar variations
- [ ] Footer components
- [ ] Image guidelines
- [ ] Animation library
- [ ] Dark mode theme
- [ ] Multiple page navigation

## 🤝 Contributing

This is an educational project created as part of Codecademy's design system curriculum. Feel free to:

1. Fork the repository
2. Create your feature branch
3. Add new components or improvements
4. Test across different browsers
5. Submit suggestions or improvements

## 📝 License

This project is created for educational purposes. Feel free to use and modify for your own learning and projects.

## 🙏 Acknowledgments

- Created as part of Codecademy's Front-End Engineer path
- Inspired by design systems from Salesforce Lightning, Google Material Design, and Bootstrap
- Fonts provided by Google Fonts

---

**Built with ❤️ for learning and practice**
