# Professional Resume Webpage - ITMD 441 Lab 1

A modern, responsive resume website built with semantic HTML5 and professional CSS3 styling, hosted on GitHub Pages.

## Overview

This project is a personal resume webpage that showcases professional information including education, skills, work experience, and projects. The website is fully responsive and works seamlessly on desktop, tablet, and mobile devices.

## Features

### Content Requirements
✅ **Header** - Name, desired role, and contact links (Email, GitHub, LinkedIn)
✅ **Professional Summary** - Brief career objective and introduction
✅ **Education** - Degree program and expected graduation date
✅ **Skills** - Eight core technical and soft skills
✅ **Experience** - Work experience/internships with descriptions
✅ **Projects** - Multiple projects with descriptions and links
✅ **Image** - Professional headshot/profile image with alt text
✅ **Footer** - Copyright notice and GitHub Pages attribution

### Technical Features
✅ **Pure HTML & CSS** - No JavaScript used
✅ **Semantic HTML5** - Proper use of `<header>`, `<main>`, `<section>`, `<article>`, `<footer>`
✅ **Custom Styling** - All elements styled (no browser defaults)
✅ **CSS Layout** - Flexbox and CSS Grid for modern layouts
✅ **Responsive Design** - Mobile-first approach with breakpoints at 768px and 480px
✅ **Accessibility** - Descriptive alt text, semantic markup, proper heading hierarchy
✅ **Interactive Elements** - Hover states, transitions, and visual feedback
✅ **Print-Friendly** - Optimized print styles for PDF export

## Responsive Breakpoints

- **Desktop**: Full layout with 3-column grid for skills
- **Tablet (≤768px)**: Adjusted font sizes, 2-column grid
- **Mobile (≤480px)**: Single column layout, optimized touch targets

## Files

- `index.html` - Main resume webpage with semantic structure
- `styles.css` - Complete styling with responsive design
- `.gitignore` - Git ignore file for common patterns

## Setup Instructions

### Prerequisites
- Git installed on your system
- GitHub account
- A code editor (VS Code recommended)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/lab1-441-ITMD.git
   cd lab1-441-ITMD
   ```

2. **Customize your resume**
   - Open `index.html` in your code editor
   - Replace placeholder text with your information:
     - Name and desired role
     - Contact information (email, GitHub, LinkedIn)
     - Education details
     - Skills (at least 5, up to 8)
     - Work experience or projects
   
3. **Add your profile image**
   - Replace `profile.jpg` with your image
   - Ensure image is in the same directory
   - Image dimensions: 200x200px recommended
   - Format: JPG, PNG, or WebP

4. **View locally**
   - Open `index.html` in your browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

### GitHub Pages Deployment

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "feat: add initial resume content"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "GitHub Pages" section
   - Select "Source" → "main branch"
   - Save and wait for deployment (usually takes 1-2 minutes)

3. **Access your site**
   - Your resume is now live at: `https://yourusername.github.io/lab1-441-ITMD`

## Customization Guide

### Updating Your Information

Edit the following sections in `index.html`:

```html
<h1 class="name">Your Name</h1>
<p class="title">Your Desired Role</p>

<!-- Contact Links -->
<a href="mailto:your.email@example.com">Email</a>
<a href="https://github.com/yourusername">GitHub</a>
<a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
```

### Color Scheme

The default color scheme uses:
- Primary Blue: `#0066cc`
- Dark Blue: `#0052a3`
- Text Color: `#333`
- Background: `#f8f9fa`

To change colors, edit the CSS values in `styles.css` or modify these color variables in the `:root` selector.

### Typography

Font family: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`

To change fonts, update the `body` selector in `styles.css`:
```css
body {
    font-family: 'Your Font Name', fallback-font;
}
```

### Layout Adjustments

- **Container Width**: Default max-width is 900px (modify in `.container` selector)
- **Spacing**: Padding and margins can be adjusted in `styles.css`
- **Grid Columns**: Skill items use `repeat(auto-fit, minmax(200px, 1fr))` for flexible columns

## Best Practices Implemented

1. **Accessibility**
   - Semantic HTML structure
   - Descriptive alt text for images
   - Proper heading hierarchy
   - Sufficient color contrast

2. **Performance**
   - Minimal CSS
   - No external dependencies
   - Optimized for fast loading
   - Print-friendly styling

3. **Maintainability**
   - Clear, commented CSS sections
   - Organized HTML structure
   - Consistent naming conventions
   - Mobile-first responsive design

## Commits

This project demonstrates regular, meaningful commits:
- Initial HTML structure
- CSS styling and layout
- Responsive design implementation
- Content customization

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Troubleshooting

### Images Not Showing
- Ensure image file is in the same directory as `index.html`
- Check file name matches in the `<img>` tag exactly
- Verify image format is supported (JPG, PNG, WebP)

### Styling Not Applied
- Clear browser cache (Ctrl+Shift+Delete)
- Ensure `styles.css` is in the same directory
- Verify CSS file path in HTML: `<link rel="stylesheet" href="styles.css">`

### GitHub Pages Not Publishing
- Check repository is public
- Verify GitHub Pages is enabled in Settings
- Wait a few minutes for deployment
- Check the "Deployments" tab for status

## Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [HTML5 Semantic Elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)
- [CSS Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

## License

This project is open source and available for personal and educational use.

## Contact

For questions or feedback about this project, please contact the author.

---

**Note**: Remember to update the image file path, contact information, and all personal details before deploying to GitHub Pages!