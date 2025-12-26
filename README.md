# EmbedExpert - Embedded Systems Consulting Website

Professional website for EmbedExpert, a leading embedded systems consulting firm specializing in Embedded Linux, Zephyr RTOS, and custom firmware development.

## 🚀 Features

### Website Features
- **Responsive Design**: Mobile-first design that works on all devices
- **Modern UI/UX**: Clean, professional interface with smooth animations
- **Complete Sections**:
  - Hero section with compelling CTA
  - About section with company stats
  - Services showcase
  - Technologies expertise
  - Portfolio/Projects gallery
  - Client testimonials
  - Contact form
  - Professional footer

### Blog System Features
- **Markdown-Based**: Write blog posts in Markdown format
- **Dynamic Loading**: Posts loaded dynamically from folder structure
- **Syntax Highlighting**: Code blocks with Highlight.js (Atom One Dark theme)
- **Category Filtering**: Filter posts by category
- **Featured Posts**: Mark important posts as featured
- **Organized Structure**: Posts organized in `blog/{category}/{slug}/` folders
- **SEO-Friendly**: Clean URLs and metadata

## 📁 Project Structure

```
OpenEmbedded/
├── index.html              # Main homepage
├── blog-dynamic.html       # Dynamic blog system
├── blog.html              # Static blog (legacy)
├── case-studies.html      # Case studies showcase
├── documentation.html     # Technical documentation
├── faq.html              # FAQ page
├── resources.html        # Resources hub
├── privacy-policy.html   # Privacy policy
├── terms.html            # Terms of service
├── blog/                 # Blog posts directory
│   ├── linux-kernel/     # Linux kernel category
│   │   └── building-custom-kernel/
│   │       └── article.md
│   ├── zephyr-rtos/      # Zephyr RTOS category
│   │   └── getting-started-zephyr/
│   │       └── article.md
│   ├── firmware/         # Firmware category
│   │   └── bootloader-development/
│   │       └── article.md
│   └── iot/             # IoT category
│       └── mqtt-protocol-embedded/
│           └── article.md
├── blog-index.json       # Generated blog index
├── generate-blog-index.js # Blog index generator
├── robots.txt            # SEO configuration
├── sitemap.xml           # Site structure
├── README.md             # Main documentation
├── BLOG_SYSTEM.md        # Blog system documentation
├── BLOG_QUICKSTART.md    # Quick start guide
├── DEPLOYMENT.md         # Deployment instructions
└── TODO.md              # Development roadmap
```

## 🎨 Technologies Used

- HTML5
- CSS3 (Modern CSS with Grid & Flexbox)
- JavaScript (Vanilla JS)
- Font Awesome 6.4.0 (Icons)
- Google Fonts (Inter & Fira Code)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Breakpoints

- Desktop: > 768px
- Mobile: ≤ 768px

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. For development, use a local server (e.g., Live Server in VS Code)

## 📝 Customization

### Update Company Information

1. **Contact Details**: Update in the Contact section (line ~1135)
2. **Company Name**: Search and replace "EmbedExpert" throughout the file
3. **Social Links**: Update href values in the footer (line ~1205)
4. **Email/Phone**: Update in contact info section

### Add Your Content

1. **Services**: Modify service cards in Services section
2. **Portfolio**: Add your actual projects in Portfolio section
3. **Testimonials**: Replace with real client testimonials
4. **About**: Update company story and statistics

## 🔧 Backend Integration

The contact form currently shows an alert. To integrate with a backend:

1. **Option 1**: Use a form service (Formspree, Netlify Forms, etc.)
2. **Option 2**: Create your own API endpoint
3. **Option 3**: Use serverless functions (AWS Lambda, Netlify Functions)

Example backend integration:
```javascript
fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify(formData)
})
```

## 📊 SEO Optimization

The website includes:
- Meta descriptions
- Semantic HTML5
- Proper heading hierarchy
- Alt text for icons (add for images)
- Mobile-friendly design

### Next Steps for SEO:

1. Add `robots.txt` file
2. Create `sitemap.xml`
3. Add Open Graph meta tags
4. Implement schema.org markup
5. Add Google Analytics

## 🎯 Performance Tips

1. Optimize images before adding them
2. Use lazy loading for images
3. Minify CSS and JavaScript for production
4. Consider using a CDN
5. Enable GZIP compression on server

## 📄 License

© 2024 EmbedExpert. All rights reserved.

## 👥 Support

For questions or support, contact: contact@embedexpert.com

## 🔄 Version History

- **v1.0.0** (2024-11-01): Initial professional website launch
  - Complete responsive design
  - All essential sections
  - Contact form
  - Testimonials and portfolio
