# Ashmit Sethi - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript, inspired by the Point theme. This static site showcases my experience in machine learning research, leadership roles, and technical projects.

## Features

- **Responsive Design**: Optimized for all device sizes
- **Modern UI**: Clean, professional design inspired by Point theme
- **Interactive Elements**: Smooth scrolling, animations, and hover effects
- **Mobile-Friendly**: Hamburger menu and touch-optimized navigation
- **Performance Optimized**: Fast loading with efficient CSS and JavaScript

## Sections

- **Hero**: Introduction and call-to-action
- **About**: Personal background and technical skills
- **Education**: UC Berkeley academic information
- **Experience**: Research assistant positions
- **Projects**: Featured technical projects
- **Leadership**: HowToHackathon and DevFinTech roles
- **Awards**: Academic and competitive achievements
- **Contact**: Multiple ways to get in touch

## Deployment on GitHub Pages

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial portfolio website"
   git push origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Access Your Site**:
   - Your site will be available at: `https://yourusername.github.io/Portfolio-1`
   - It may take a few minutes to deploy

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --accent-color: #f59e0b;
    /* ... other variables */
}
```

### Content
- Update personal information in `index.html`
- Modify the hero section description
- Add or remove projects, experience, or skills
- Update contact information

### Styling
- All styles are in `styles.css`
- Uses CSS Grid and Flexbox for layouts
- Responsive breakpoints at 768px and 480px
- Smooth transitions and hover effects

## File Structure

```
Portfolio-1/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Performance

- Optimized CSS with custom properties
- Debounced scroll events
- Lazy loading ready for images
- Minimal JavaScript footprint
- Fast loading times

---

Built with ❤️ by Ashmit Sethi
