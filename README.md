# Bethel Evangelical Church of Michigan - Website

A modern, responsive website for Bethel Evangelical Church of Michigan, built with HTML, CSS, and JavaScript.

## 🌟 Features

### Design & User Experience
- **Modern & Professional Design**: Clean, elegant design appropriate for a church
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle scroll animations and hover effects
- **Beautiful Typography**: Uses Google Fonts (Inter & Playfair Display)
- **Gradient Accents**: Modern purple gradient theme throughout

### Navigation & Structure
- **Fixed Navigation Bar**: Always accessible with smooth scrolling
- **Mobile-Friendly Menu**: Hamburger menu for mobile devices
- **Active Section Highlighting**: Navigation shows current section
- **Smooth Scrolling**: Seamless navigation between sections

### Content Sections
1. **Hero Section**: Welcoming banner with call-to-action buttons
2. **About Section**: Mission, vision, and values
3. **Services Section**: Worship service times and descriptions
4. **Ministries Section**: Church ministries and programs
5. **Events Section**: Upcoming church events
6. **Contact Section**: Contact information and contact form
7. **Footer**: Additional links and social media

### Interactive Features
- **Contact Form**: Functional form with validation
- **Notification System**: Success/error messages for form submissions
- **Scroll Animations**: Elements fade in as you scroll
- **Hover Effects**: Interactive elements respond to user interaction
- **Service Countdown**: Shows time until next service (optional feature)

## 📁 File Structure

```
BethelWebsite/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This documentation file
└── Website             # Original project file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. The website will load immediately - no server setup required

### Local Development
For development purposes, you can use any local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The website uses a purple gradient theme. To change colors, modify these CSS variables in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Text colors */
color: #333; /* Main text */
color: #666; /* Secondary text */
```

### Content
- **Church Information**: Update contact details, service times, and address in `index.html`
- **Images**: Replace placeholder images with actual church photos
- **Events**: Update the events section with real upcoming events
- **Ministries**: Modify ministry descriptions to match your church's programs

### Fonts
The website uses Google Fonts:
- **Inter**: For body text and general content
- **Playfair Display**: For headings and titles

To change fonts, update the Google Fonts link in the HTML head section.

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

Key responsive features:
- Mobile hamburger menu
- Flexible grid layouts
- Responsive typography
- Touch-friendly buttons and links

## 🔧 Technical Details

### HTML5 Features
- Semantic HTML structure
- Accessibility-friendly markup
- SEO-optimized meta tags
- Proper heading hierarchy

### CSS3 Features
- CSS Grid and Flexbox layouts
- CSS animations and transitions
- Custom properties (variables)
- Media queries for responsiveness

### JavaScript Features
- ES6+ syntax
- Intersection Observer API for scroll animations
- Form validation
- Dynamic content updates
- Event handling

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📞 Contact Information

The website includes placeholder contact information. Update these details in `index.html`:

- **Address**: 123 Church Street, Michigan, MI 48100
- **Phone**: (555) 123-4567
- **Email**: info@bethelchurchmi.org
- **Office Hours**: Monday - Friday: 9:00 AM - 5:00 PM

## 🎯 SEO Features

- Meta description and title tags
- Semantic HTML structure
- Alt text for images (when added)
- Clean URL structure
- Fast loading times

## 🔒 Security Considerations

- Form validation on both client and server side
- XSS protection through proper input sanitization
- HTTPS ready (when deployed)

## 🚀 Deployment

### Static Hosting
The website can be deployed to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Firebase Hosting

### Domain Setup
1. Purchase a domain (e.g., bethelchurchmi.org)
2. Configure DNS settings
3. Upload files to your hosting provider
4. Set up SSL certificate (recommended)

## 📈 Analytics & Tracking

To add analytics, include tracking codes in the HTML head section:

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

This is a church website template. Feel free to:
- Customize the design and content
- Add new features
- Improve accessibility
- Optimize performance

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Google Fonts for typography
- Font Awesome for icons
- Unsplash for placeholder images
- Modern CSS techniques and best practices

---

**Built with ❤️ for Bethel Evangelical Church of Michigan** 