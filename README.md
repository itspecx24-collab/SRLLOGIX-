# SRL-LOGIX Static Website

A fully static, production-ready logistics website built with HTML, CSS, and JavaScript for GitHub Pages deployment.

## 🚀 Features

- **Responsive Design**: Mobile-first approach using Bootstrap 5 grid system
- **Modern UI**: Clean, professional design with smooth animations
- **SEO Optimized**: Meta tags, structured data, and sitemap included
- **Interactive Elements**: Gallery with lightbox, logistics quiz, contact forms
- **Performance**: Lazy loading, optimized images, minified assets
- **Accessibility**: Semantic HTML5, ARIA labels, keyboard navigation

## 📁 Project Structure

```
windsurf-project-2/
├── index.html                 # Homepage
├── about.html                 # About page
├── contact.html               # Contact page
├── sitemap.xml               # SEO sitemap
├── robots.txt                # Search engine instructions
├── README.md                 # This file
├── assets/
│   ├── css/
│   │   ├── style.css         # Main styles
│   │   └── components.css    # Component styles
│   ├── js/
│   │   └── main.js          # JavaScript functionality
│   └── images/              # All image assets
├── services/
│   ├── consolidation.html    # Consolidation services
│   ├── ior-eor.html         # IOR/EOR services
│   ├── customs-clearance.html # Customs clearance
│   └── freight-forwarding.html # Freight forwarding
└── portals/
    ├── client-portal.html   # Client portal (Coming Soon)
    ├── tracking.html        # Tracking portal (Coming Soon)
    └── documentation.html   # Documentation portal (Coming Soon)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup, accessibility features
- **CSS3**: Custom properties, flexbox, grid, animations
- **JavaScript ES6+**: Modern JS with DOM manipulation
- **Bootstrap 5**: Grid system, components, utilities
- **Font Awesome**: Icon library
- **Google Fonts**: Typography

## 📱 Pages Overview

### Homepage (`index.html`)
- Hero section with animated background
- Services overview cards
- Interactive gallery with lightbox
- Logistics knowledge quiz
- Customer testimonials
- Contact call-to-action

### Service Pages
- **Consolidation**: Cost-effective shipping solutions
- **IOR/EOR**: Importer/Exporter of Record services
- **Customs Clearance**: Professional customs brokerage
- **Freight Forwarding**: Air, sea, and land transport

### Portal Pages
- **Client Portal**: Dashboard preview (Coming Soon)
- **Tracking Portal**: Real-time shipment tracking (Coming Soon)
- **Documentation Portal**: Document management (Coming Soon)

### Other Pages
- **About**: Company information, team, values
- **Contact**: Contact form, map, FAQ

## 🎨 Design Features

### Color Scheme
- Primary: #007bff (Blue)
- Secondary: #6c757d (Gray)
- Success: #28a745 (Green)
- Warning: #ffc107 (Yellow)
- Danger: #dc3545 (Red)

### Typography
- Headings: 'Montserrat', sans-serif
- Body: 'Open Sans', sans-serif
- Icons: Font Awesome 6.4.0

### Responsive Breakpoints
- Mobile: < 576px
- Tablet: 576px - 768px
- Desktop: 768px - 992px
- Large: > 992px

## ⚡ Performance Optimizations

- **Lazy Loading**: Images load as needed
- **Minified Assets**: CSS and JS optimized
- **Optimized Images**: WebP format with fallbacks
- **CDN Usage**: Bootstrap and Font Awesome from CDN
- **Caching Headers**: Proper cache control

## 🔧 Customization

### Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-color: #007bff;
    --secondary-color: #6c757d;
    /* ... */
}
```

### Contact Information
Update contact details in all HTML files:
- Phone numbers
- Email addresses
- Physical addresses
- Social media links

### Images
Replace images in `assets/images/`:
- Logo: `logo.png`
- Hero background: `L1.gif`
- Service images: Various .jpg files
- Team photos: `team-*.jpg`

## 🚀 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main` or `gh-pages`)
4. Site will be available at `https://username.github.io/repository-name`

### Manual Deployment
1. Upload all files to web server
2. Ensure server supports static file hosting
3. Configure domain if needed

## 📊 SEO Features

- **Meta Tags**: Title, description, keywords on all pages
- **Structured Data**: JSON-LD schema for organization
- **Sitemap**: Complete sitemap.xml for search engines
- **Robots.txt**: Proper search engine instructions
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Alt Text**: All images have descriptive alt attributes

## 🔄 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Android Chrome)

## 🛡️ Security

- **No Server Dependencies**: Pure static site
- **HTTPS Ready**: Works perfectly with SSL
- **No User Input Storage**: Contact forms are frontend-only
- **CSP Compatible**: Works with Content Security Policy

## 📈 Analytics Integration

Add Google Analytics or other tracking to `index.html` before closing `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Make changes
4. Test thoroughly
5. Submit pull request

## 📝 License

This project is proprietary to SRL-LOGIX. All rights reserved.

## 📞 Support

For technical support or questions:
- Email: srlmsocial@gmail.com
- Phone: 0789858837

## 🗺️ Roadmap

### Phase 1 (Current)
- ✅ Static website with all pages
- ✅ Responsive design
- ✅ SEO optimization
- ✅ Interactive features

### Phase 2 (Future)
- 🔄 Backend API integration
- 🔄 User authentication
- 🔄 Real shipment tracking
- 🔄 Document management system

### Phase 3 (Future)
- 🔄 Payment processing
- 🔄 Advanced analytics
- 🔄 Multi-language support
- 🔄 Mobile app integration

---

**Built with ❤️ for SRL-LOGIX**
