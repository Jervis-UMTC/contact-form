# Contact Form

A modern, responsive contact form built with HTML and CSS featuring a dark theme and smooth animations.

## Features

- **Responsive Design**: Automatically adapts to different screen sizes using CSS Grid
- **Dark Theme**: Modern dark color scheme with green accent colors
- **Smooth Animations**: Fade-in animation on page load and hover effects
- **Form Validation**: HTML5 form validation with required fields
- **Icon Integration**: Font Awesome icons for visual enhancement
- **Accessibility**: Proper focus states and semantic HTML structure

## Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Font Awesome 7.0.0 (CDN)

## File Structure

```
contact-form/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
└── README.md          # This file
```

## Installation

1. Clone or download the files
2. Open `index.html` in your web browser
3. No build process or dependencies required

## Form Fields

- **Name** (required)
- **Email** (required)
- **Phone** (optional)
- **Subject** (required)
- **Message** (required, textarea)

## Design Features

### Color Scheme
- Primary Green: `#4ADE80`
- Dark Green: `#22C55E`
- Background: `#1A1A1A`
- Card Background: `#252525`
- Input Background: `#333`

### Responsive Breakpoints
- Desktop: Auto-fit grid with 300px minimum column width
- Mobile (≤600px): Single column layout

### Animations
- Page load: Fade-in with slight upward movement
- Button hover: Lift effect with shadow
- Input focus: Border color change with glow effect

## Browser Support

Modern browsers supporting:
- CSS Grid
- CSS Custom Properties (Variables)
- CSS Transforms and Transitions

## Customization

### Colors
Modify the CSS custom properties in `:root` to change the color scheme:

```css
:root {
  --primary-color: #4ADE80;
  --primary-dark: #22C55E;
  --bg-dark: #1A1A1A;
  /* ... other colors */
}
```

### Layout
Adjust the grid template in `.input-group` to change the responsive behavior:

```css
.input-group {
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}
```

## Form Integration

Currently, the form is front-end only. To make it functional, you'll need to:

1. Add a `action` attribute to the `<form>` tag
2. Set up a backend endpoint to handle form submissions
3. Add JavaScript for client-side validation (optional)

## License

Free to use for personal and commercial projects.

## Contributing

Feel free to submit issues and pull requests to improve the design or functionality.
