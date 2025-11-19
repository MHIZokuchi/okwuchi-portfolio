# Okwuchi Uzoigwe - Professional Portfolio

A modern, responsive portfolio website showcasing professional experience, technical expertise, recognition, and community involvement.

## 🚀 Quick Start

### Option 1: GitHub Pages Deployment (Recommended)

1. **Create a new repository** named `okwuchi-portfolio` on GitHub

2. **Clone this repository locally**:
   ```bash
   git clone https://github.com/yourusername/okwuchi-portfolio.git
   cd okwuchi-portfolio
   ```

3. **Push the files to GitHub**:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git push origin main
   ```

4. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Set source to "main" branch
   - Save
   - Your site will be live at: `https://yourusername.github.io/okwuchi-portfolio`

### Option 2: Using GitHub Pages Default Domain

If you rename the repository to `yourusername.github.io`:
- Files will be automatically published to: `https://yourusername.github.io`

### Option 3: Local Testing

To test locally before deploying:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server installed)
npx http-server
```

Then visit `http://localhost:8000`

## 📁 File Structure

```
okwuchi-portfolio/
├── index.html          # Main portfolio page
├── styles.css          # All styling (modern, responsive design)
├── script.js           # Interactivity and animations
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## 🎨 Features

- **Responsive Design**: Looks great on mobile, tablet, and desktop
- **Modern Styling**: Clean, professional aesthetic with gradient hero
- **Smooth Animations**: Fade-in effects on scroll, hover states
- **Section Navigation**: Sticky navbar with smooth scrolling
- **SEO Optimized**: Proper semantic HTML structure
- **Performance**: Pure HTML/CSS/JS (no external dependencies)

## 📝 Customization

### Update Personal Information

1. **Hero Section**: Edit the main heading and description in `index.html`
2. **Social Links**: Update contact section with your actual social media links
3. **Featured Work**: Modify work cards with your projects
4. **Recognition**: Update award dates and descriptions
5. **Community**: Personalize mentorship and speaking details

### Color Scheme

Update CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1e40af;          /* Main blue */
    --secondary-color: #0369a1;        /* Secondary blue */
    --accent-color: #f59e0b;           /* Yellow accent */
    /* ... other colors ... */
}
```

### Fonts

The portfolio uses "Inter" from Google Fonts. To change:
1. Replace the Google Fonts link in `<head>`
2. Update the font-family in CSS

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables and Grid/Flexbox
- **JavaScript**: Vanilla JS (no frameworks)
- **Google Fonts**: "Inter" typeface

## 📱 Responsive Breakpoints

- Desktop: 1200px width container
- Tablet: 768px
- Mobile: Optimized for all screen sizes

## 🌐 Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support
- IE11: Basic support

## 📊 SEO Optimization

- Semantic HTML with proper heading hierarchy
- Meta tags for viewport and charset
- Descriptive page title
- Structured content

## 🚀 Performance

- Lightweight (no external dependencies)
- Fast load times (minimal CSS and JS)
- Optimized for Core Web Vitals
- CSS Grid for efficient layouts

## 📞 Contact & Updates

When you update the portfolio:

1. **Edit locally** and test with `python -m http.server`
2. **Commit changes**:
   ```bash
   git add .
   git commit -m "Update portfolio with new projects"
   git push
   ```
3. **GitHub Pages** automatically deploys on push

## 📚 Additional Resources

- [GitHub Pages Documentation](https://pages.github.com/)
- [Web Design Best Practices](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [CSS-Tricks](https://css-tricks.com/)

## ✅ Pre-Launch Checklist

- [ ] Update all social media links
- [ ] Verify email address
- [ ] Review all text for typos
- [ ] Test on mobile device
- [ ] Check all external links work
- [ ] Verify GitHub Pages is enabled
- [ ] Share portfolio URL

## 📄 License

This portfolio template is provided as-is. Feel free to customize and use it as your own.

---

**Created for Okwuchi Uzoigwe | Senior Software Engineer | 2025**

Last updated: 2025-11-19
