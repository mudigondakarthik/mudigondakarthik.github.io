# Karthik Mudigonda - Digital Marketer Portfolio Website

A premium, modern, multi-page portfolio website featuring 3D elements, smooth animations, and professional design.

## 🌟 Features

### Design & UI
- **Premium Modern Design**: Agency-level quality with distinctive aesthetics
- **3D Interactive Elements**: Dynamic 3D card animations and parallax effects
- **Smooth Animations**: Fade-in effects, scroll animations, and micro-interactions
- **Responsive Layout**: Fully responsive across all devices
- **Custom Typography**: Playfair Display for headings, Work Sans for body text
- **Professional Color Palette**: Sophisticated dark blues with vibrant accent colors

### Pages Included (5 Complete Pages)

1. **Home Page (index.html)**
   - Hero section with animated 3D card
   - Key skills highlights
   - Metrics showcase
   - Featured work preview
   - Floating background shapes

2. **About Me Page (about.html)**
   - Professional summary
   - Career journey timeline
   - Education details
   - Core values section
   - Tools & platforms showcase

3. **Skills & Services Page (skills.html)**
   - Skills organized by categories
   - 6 detailed service offerings
   - Benefit-focused descriptions
   - Interactive hover effects

4. **Portfolio Page (portfolio.html)**
   - Filter tabs for project categories
   - 6 detailed case studies
   - Results metrics for each project
   - Client testimonials
   - Hover overlay effects

5. **Contact Page (contact.html)**
   - Professional contact form
   - Contact information cards
   - Social media links
   - FAQ section
   - Availability status

### Technical Features
- Sticky navigation header
- Mobile-responsive menu
- Smooth scroll behavior
- Intersection Observer animations
- Counter animations for metrics
- Form validation and success states
- 3D card mouse tracking
- Parallax scrolling effects
- Portfolio filtering system

## 📁 File Structure

```
portfolio/
├── index.html          # Home page
├── about.html          # About me page
├── skills.html         # Skills & services page
├── portfolio.html      # Portfolio/work page
├── contact.html        # Contact page
├── styles.css          # Complete stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Setup Instructions

### Quick Start
1. Download all files to a single folder
2. Open `index.html` in a modern web browser
3. That's it! The website is ready to use

### Local Development
1. Extract all files to a folder
2. Use a local server (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```
3. Open http://localhost:8000 in your browser

### Deployment Options

**GitHub Pages:**
1. Create a new repository
2. Upload all files
3. Enable GitHub Pages in settings
4. Your site will be live at `username.github.io/repo-name`

**Netlify:**
1. Drag and drop the folder to Netlify
2. Site goes live instantly with free hosting

**Vercel:**
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project folder
3. Follow the prompts

## 🎨 Customization Guide

### Colors
Edit CSS variables in `styles.css` (lines 6-15):
```css
:root {
    --primary: #1a1a2e;        /* Main dark color */
    --accent: #e94560;         /* Primary accent */
    --accent-light: #ff6b8a;   /* Light accent */
    /* Add your custom colors */
}
```

### Content
- Update text content directly in HTML files
- Replace placeholder contact info in `contact.html`
- Add your social media links (search for `href="#"`)
- Update project descriptions in `portfolio.html`

### Images
- Add your photos to replace `.work-placeholder` elements
- Update background gradients for portfolio items
- Add profile photo in `about.html`

### Typography
Change fonts in `styles.css`:
```css
:root {
    --font-display: 'Your Display Font', serif;
    --font-body: 'Your Body Font', sans-serif;
}
```
Remember to update the Google Fonts link in HTML files.

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- Desktop: 1280px and above
- Tablet: 768px to 1279px
- Mobile: Below 768px

## ⚡ Performance Optimizations

- CSS variables for consistent theming
- Efficient animations using CSS transforms
- Intersection Observer for scroll animations
- Lazy loading support
- Optimized JavaScript
- Minimal dependencies (no frameworks required)

## 🎯 Key Design Principles

1. **Professional First**: Agency-quality design
2. **User Experience**: Smooth, intuitive navigation
3. **Performance**: Fast loading, optimized code
4. **Accessibility**: Semantic HTML, proper contrast
5. **Modern**: Latest design trends and techniques

## 📝 Content Checklist

Before going live, update:
- [ ] All text content with your information
- [ ] Social media links (LinkedIn, Instagram, Twitter)
- [ ] Email address in contact form
- [ ] Portfolio project descriptions
- [ ] Skills and services offered
- [ ] Testimonials (if available)
- [ ] Meta tags for SEO (title, description)
- [ ] Favicon (add favicon.ico)

## 🛠️ Adding New Features

### Add a Blog Page
1. Create `blog.html` following the structure of other pages
2. Add navigation link in all HTML files
3. Style using existing CSS classes

### Connect Contact Form
Replace form handler in `script.js`:
```javascript
// Replace the fetch URL with your backend endpoint
fetch('YOUR_API_ENDPOINT', {
    method: 'POST',
    body: JSON.stringify(formData)
})
```

### Add Analytics
Before `</head>` tag, add:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
```

## 📧 Support & Contact

For questions about customization or deployment:
- Check browser console for any errors
- Ensure all files are in the same directory
- Verify file names match exactly (case-sensitive)

## 📄 License

This portfolio template is provided as-is. Feel free to customize and use for your personal portfolio.

## 🎉 Credits

**Design & Development**: Professional portfolio template
**Fonts**: Google Fonts (Playfair Display, Work Sans)
**Icons**: Custom SVG icons

---

**Version**: 1.0
**Last Updated**: January 2026

Happy showcasing your work! 🚀
