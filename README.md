# John Aguillard - Personal Website

A modern, responsive personal website for John Aguillard, showcasing his experience as a Product Manager and RF Engineer with expertise in robotics, aerospace technology, and autonomous systems.

## 🚀 Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with Bootstrap 5
- **Single Page + Multi-Page**: Main single-page site with dedicated pages for detailed content
- **Contact Form**: Integrated with Formspree for message handling
- **Accessibility**: Semantic HTML, ARIA labels, and keyboard navigation support
- **Performance**: Optimized loading, compressed images, and efficient CSS/JS
- **SEO Ready**: Meta tags, structured data, and search engine optimization

## 📁 File Structure

```
├── index.html          # Main homepage (single-page design)
├── resume.html         # Detailed resume page
├── projects.html       # Projects showcase page
├── contact.html        # Contact form and information
├── styles.css          # Custom CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

### Option 1: GitHub Pages (Recommended)
1. Fork or download this repository
2. Upload files to your GitHub repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Web Hosting
1. Download all files
2. Upload to your web hosting provider's public directory
3. Ensure `index.html` is in the root directory
4. Configure your domain if needed

### Option 3: Local Development
1. Download all files to a local directory
2. Open `index.html` in a web browser
3. For best results, serve through a local web server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

## ⚙️ Customization Guide

### Personal Information
Update the following in `index.html`:
- Name and title in the `<title>` tag and hero section
- Professional summary in the hero section
- Contact email in the contact section
- Social media links in the contact section and footer

### Contact Form Setup
1. Sign up for a free account at [Formspree.io](https://formspree.io/)
2. Create a new form and get your form endpoint
3. Replace `https://formspree.io/f/your_form_id` in both `index.html` and `contact.html` with your actual endpoint

### Resume Content
Edit `resume.html` to update:
- Professional experience details
- Education information
- Skills and certifications
- Accomplishments and projects

### Profile Image
Replace the placeholder image URL:
- Current: `https://via.placeholder.com/300x300?text=John+Aguillard`
- Update with your actual photo URL or upload an image to your hosting

### Color Scheme
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;    /* Main brand color */
    --secondary-color: #1e40af;  /* Secondary brand color */
    --accent-color: #3b82f6;     /* Accent color */
    --dark-color: #1f2937;       /* Dark text color */
    --light-color: #f8fafc;      /* Light background color */
}
```

### Fonts
The site uses Inter font by default. To change:
1. Add your font link in the `<head>` section
2. Update the `font-family` in `styles.css`

## 🎨 Design Features

### Color Palette
- **Primary Blue**: #2563eb (Professional, trustworthy)
- **Secondary Blue**: #1e40af (Depth, authority)
- **Accent Blue**: #3b82f6 (Modern, tech-forward)
- **Dark Gray**: #1f2937 (Readability)
- **Light Gray**: #f8fafc (Clean backgrounds)

### Typography
- **Headings**: Inter font family, bold weights
- **Body Text**: Inter font family, regular weight
- **Responsive**: Fluid typography that scales with screen size

### Layout
- **Desktop**: Multi-column layouts with sidebar content
- **Tablet**: Adapted layouts with stacked sections
- **Mobile**: Single-column, touch-friendly design

## 📱 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile browsers**: iOS Safari 14+, Chrome Mobile 90+

## 🔧 Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Custom Properties
- **JavaScript**: ES6+, Vanilla JS (no frameworks)
- **Bootstrap 5**: Responsive framework
- **Font Awesome**: Icon library

## 📊 Performance Optimizations

- Compressed and optimized images
- Minified CSS and JavaScript
- Efficient font loading
- Lazy loading for images
- Reduced HTTP requests

## 🚀 Deployment Checklist

Before going live:
- [ ] Update all personal information
- [ ] Replace placeholder images
- [ ] Configure contact form with Formspree
- [ ] Update social media links
- [ ] Test on multiple devices
- [ ] Validate HTML and CSS
- [ ] Check accessibility compliance
- [ ] Test contact form submission
- [ ] Verify all links work
- [ ] Check loading speed

## 📈 SEO Recommendations

1. **Meta Tags**: Update title, description, and keywords
2. **Alt Text**: Add descriptive alt text to all images
3. **Structured Data**: Consider adding JSON-LD markup
4. **XML Sitemap**: Create and submit to search engines
5. **Google Analytics**: Add tracking code if desired

## 🛡️ Security Best Practices

- Keep dependencies updated
- Use HTTPS for hosting
- Validate all form inputs
- Implement CSP headers if possible
- Regular security audits

## 📞 Support

For technical issues or customization help:
- Check the code comments for guidance
- Refer to Bootstrap 5 documentation
- Font Awesome icon documentation
- Formspree setup guides

## 📄 License

This website template is created for John Aguillard's personal use. Feel free to use as inspiration for your own projects, but please don't copy the personal content directly.

## 🔄 Version History

- **v1.0**: Initial release with full functionality
- Professional single-page and multi-page design
- Complete contact form integration
- Mobile-responsive layout
- Accessibility features

---

**Built with ❤️ for showcasing engineering excellence**