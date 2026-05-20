# SSNENG - Seismic Analysis & Design of Structures

![Website Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

A modern, responsive website for SSNENG - a professional organization specializing in seismic analysis and structural design for earthquake-resistant engineering.

## 🌟 Features

### Core Features
- ✅ **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Modern UI/UX** - Professional gradient design with smooth animations
- ✅ **No Dependencies** - Pure HTML5, CSS3, and vanilla JavaScript
- ✅ **Fast Performance** - Optimized for quick load times
- ✅ **SEO Friendly** - Semantic HTML structure for better search engine visibility
- ✅ **Accessibility** - WCAG compliant markup and navigation

### Interactive Components
- 🎯 **Mobile Navigation** - Hamburger menu with smooth animations
- 📧 **Contact Forms** - Contact form with validation and newsletter signup
- 🔔 **Toast Notifications** - Real-time feedback for user interactions
- ✨ **Scroll Animations** - Elements animate as they come into view
- 🖼️ **Parallax Effects** - Dynamic hero section with parallax scrolling
- 📱 **Mobile Menu** - Fully functional mobile navigation

### Sections
1. **Navigation** - Sticky navbar with smooth scrolling links
2. **Hero Section** - Eye-catching banner with call-to-action button
3. **Services** - 6 service offerings with icons
4. **About** - Company information with statistics
5. **Expertise** - Technical skills and tools
6. **Contact** - Contact information and contact form
7. **Newsletter** - Email subscription
8. **Footer** - Social links and additional resources

## 📁 Project Structure

```
ssneng.org/
├── index.html              # Main HTML file
├── styles/
│   └── main.css           # Complete stylesheet
├── js/
│   └── main.js            # JavaScript functionality
├── README.md              # This file
└── .gitignore             # Git ignore configuration
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Font Awesome icons and fonts)

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/smaabusubhani/ssneng.org.git
   cd ssneng.org
   ```

2. **Open in browser:**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. **View the site:**
   - Open `http://localhost:8000` in your browser

## 🌐 Deployment

### GitHub Pages (Recommended)

1. Go to your repository Settings
2. Navigate to "Pages" section
3. Select "main" branch as source
4. Click "Save"
5. Your site will be available at: `https://smaabusubhani.github.io/ssneng.org`

### Custom Domain with GitHub Pages

1. Follow GitHub Pages setup above
2. Go to Settings → Pages
3. Under "Custom domain", enter your domain name
4. Click "Save"
5. Configure DNS records:
   ```
   A record: 185.199.108.153
   A record: 185.199.109.153
   A record: 185.199.110.153
   A record: 185.199.111.153
   ```

### Deploy to Netlify

1. Push code to GitHub
2. Connect Netlify to your GitHub account
3. Select the repository
4. Deploy with one click

### Deploy to Vercel

1. Push code to GitHub
2. Import project to Vercel
3. Automatic deployments on push

## 🎨 Customization

### Change Colors

Edit the CSS variables in `styles/main.css`:

```css
:root {
    --primary-color: #00a8e8;      /* Cyan */
    --secondary-color: #003d5c;    /* Dark Blue */
    --accent-color: #ff4444;       /* Red */
    --light-bg: #f8f9fa;
    --dark-bg: #1a1a1a;
}
```

### Update Content

1. **Logo & Branding:**
   - Edit `.logo` text in `index.html`
   - Update `.tagline` text

2. **Service Cards:**
   - Modify service titles and descriptions in HTML
   - Change icons from Font Awesome

3. **Company Info:**
   - Update About section with your company details
   - Modify statistics in the `.about-stats` section

4. **Contact Information:**
   - Update email, phone, and address
   - Modify form handling in `js/main.js`

### Add Your Logo

1. Place logo image in a new `images/` folder
2. Update HTML:
   ```html
   <div class="navbar-brand">
       <img src="images/logo.png" alt="SSNENG Logo" class="logo-img">
       <p class="tagline">Seismic Analysis & Design</p>
   </div>
   ```

3. Add CSS:
   ```css
   .logo-img {
       max-width: 150px;
       height: auto;
   }
   ```

## 📝 File Descriptions

### index.html
- Main HTML file with semantic structure
- Uses Font Awesome CDN for icons
- Responsive meta viewport tag
- All sections and content

### styles/main.css
- **Size:** ~12.5 KB
- Mobile-first responsive design
- CSS variables for easy customization
- Animations and transitions
- Flexbox and Grid layouts
- Breakpoints for mobile (480px) and tablet (768px)

### js/main.js
- **Size:** ~9 KB
- Hamburger menu toggle
- Active link highlighting
- Form validation and submission
- Scroll animations
- Parallax effects
- Toast notifications
- Intersection Observer API

## 🔧 JavaScript Features

### Mobile Menu
```javascript
// Automatically handled by the hamburger menu listener
```

### Form Validation
- Email format validation
- Required field checking
- Real-time feedback

### Scroll Animations
- Service cards fade in on scroll
- Expertise items animate into view
- Statistics counter animations

### Parallax Effect
- Hero background moves slower than scroll speed
- Creates depth effect

## 📱 Responsive Breakpoints

- **Desktop:** 1200px+ (2 columns for grids)
- **Tablet:** 768px - 1199px (auto-fit columns)
- **Mobile:** Below 768px (1 column)
- **Small Mobile:** Below 480px (reduced font sizes)

## 🔍 SEO Optimization

- Semantic HTML5 tags
- Meta descriptions
- Alt text for images
- Heading hierarchy (H1, H2, H3)
- Structured data ready
- Mobile-friendly design
- Fast load times

## ♿ Accessibility

- Semantic HTML elements
- ARIA labels where needed
- Keyboard navigation support
- Color contrast compliance
- Focus indicators on interactive elements
- Alt text support for images

## 📊 Performance

- Minimal CSS (compressed ~12.5 KB)
- Minimal JavaScript (~9 KB)
- No external dependencies
- Font Awesome loaded via CDN
- Optimized animations
- Lazy loading ready

## 🐛 Troubleshooting

### Menu not working
- Check browser console for JavaScript errors
- Ensure `js/main.js` is properly linked
- Clear browser cache

### Styles not loading
- Verify `styles/main.css` path is correct
- Check for CSS syntax errors
- Ensure file permissions are correct

### Forms not submitting
- Check browser console for validation errors
- Ensure all required fields are filled
- Verify email format

### Mobile menu not closing
- Clear browser cache
- Check viewport meta tag
- Test in incognito mode

## 📞 Support & Contact

- **Email:** info@ssneng.org
- **Phone:** +1 (234) 567-890
- **GitHub:** [smaabusubhani/ssneng.org](https://github.com/smaabusubhani/ssneng.org)

## 📄 License

MIT License - feel free to use this project for any purpose

## 🙏 Credits

- Font Awesome for icons
- Google Fonts
- Designed and developed with ❤️

## 🔄 Version History

### v1.0.0 - Initial Release (2026-05-20)
- Initial website launch
- All core features implemented
- Fully responsive design
- Contact forms and newsletter signup
- Performance optimizations

---

**Last Updated:** May 20, 2026

For the latest updates, visit: [https://github.com/smaabusubhani/ssneng.org](https://github.com/smaabusubhani/ssneng.org)