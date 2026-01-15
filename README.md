# Extension Yard

A single-page website to showcase Chrome browser extensions.

## Features

- Clean, modern design
- Responsive layout (mobile, tablet, desktop)
- Smooth scrolling navigation
- Individual sections for each extension
- Featured images for each extension
- Direct links to Chrome Web Store

## Customization

### Adding Your Extensions

1. Edit `index.html` and update each extension card:
   - Replace placeholder images with your extension screenshots
   - Update extension titles
   - Write descriptions for each extension
   - Add your Chrome Web Store links

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #4F46E5;  /* Main brand color */
    --secondary-color: #10B981; /* Accent color */
    /* ... other colors */
}
```

### Adding/Removing Extensions

To add more extensions, copy one of the `.extension-card` divs and paste it in the extensions section. To remove extensions, simply delete the corresponding `.extension-card` div.

## File Structure

```
extensionyard.github.io/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # JavaScript for smooth scrolling
└── README.md       # This file
```

## Images

Place your extension screenshots in an `images/` folder and update the image paths in `index.html`:

```html
<img src="images/extension1.png" alt="Extension 1" />
```

## Deployment

This site can be deployed to:
- GitHub Pages (since it's already in a `.github.io` repository)
- Netlify
- Vercel
- Any static hosting service

Simply push your files to the repository and enable GitHub Pages in the repository settings.
