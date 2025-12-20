# DJ Cosmos - Personal Website

A modern, multi-page website showcasing the biography and interests of a guitar teacher and musician.

## Project Structure

```
djcosmos/
├── index.html                  # Root redirect to biography
├── css/
│   ├── base.css               # Shared base styles and design system
│   └── main.js                # Shared JavaScript functionality
├── assets/
│   └── images/
│       └── profile-image.webp # Profile photo
├── biography/
│   ├── index.html             # Main biography/CV page
│   └── biography.css          # Biography-specific styles
└── djcosmos/
    ├── djcosmos.html          # Solar system sonification app
    └── djcosmos.css           # Sonification app styles
```

## Features

- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **Dark Mode**: Premium dark theme with vibrant accent colors
- **Glassmorphism**: Modern glass-card effects with backdrop blur
- **Smooth Animations**: Scroll-reveal animations and micro-interactions
- **Component-Based**: Separate folders for each section with their own styles
- **Shared Base**: Common design system and utilities in `css/base.css`

## Pages

### Biography (Main Page)
- Hero section with profile image
- Biography/About section
- Teaching experience timeline
- Performance history
- Skills & specializations grid
- Contact information

### DJ Cosmos
- Solar system sonification application
- Interactive planetary sound synthesis
- Real-time audio manipulation
- NASA Eyes integration
- Educational tool for music and astronomy


## Customization

### Adding a New Interest Page

1. Create a new folder: `mkdir new-interest`
2. Create HTML file: `new-interest/new-interest.html`
3. Create CSS file: `new-interest/new-interest.css`
4. Link base CSS: `<link rel="stylesheet" href="../css/base.css">`
5. Link component CSS: `<link rel="stylesheet" href="new-interest.css">`
6. Link JavaScript: `<script src="../css/main.js"></script>`
7. Update navigation in all pages to include the new link

### Updating Content

- **Profile Image**: Replace `assets/images/profile-image.webp`
- **Personal Info**: Edit the HTML files directly
- **Colors**: Modify CSS custom properties in component CSS files
- **Navigation**: Update the dropdown menu in each HTML file

## Technologies

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, Animations
- **Vanilla JavaScript**: No frameworks, pure JS for interactions
- **Google Fonts**: Inter (body) and Playfair Display (headings)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2025 José Alberto Amador Fernández.
