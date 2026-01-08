# Total Roof Care Website

A professional, modern website for Total Roof Care - a trusted roofer serving Cardiff, Bristol and surrounding areas.

## 🎨 Design Overview

This website is designed to match the elegant, professional aesthetic of the CaSA Architects template, adapted for a roofing trade business. It features:

- Clean, modern layout with elegant typography
- Full-width hero sections with compelling imagery
- Professional service showcases
- Testimonials with decorative quotation marks
- Comprehensive services checklist
- Interactive contact forms
- Fully responsive mobile-first design

## 📋 Project Structure

```
Total Roof Care/
├── index.html          # Home page
├── contact.html        # Contact page with form and map
├── portfolio.html      # Portfolio coming soon page
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Image assets folder
└── README.md           # This file
```

## 🎨 Brand Colors

- **Primary Blue**: `#1E3A8A` (Navy blue - main brand color)
- **Accent Gold**: `#D4A853` (Warm gold - accent color)
- **White**: `#FFFFFF`
- **Light Grey**: `#F5F5F5` (Backgrounds)
- **Dark Grey**: `#333333` (Text)
- **Text Grey**: `#666666` (Secondary text)

## 🖼️ Required Images

To complete the website, add the following images to the `/images/` folder:

### Critical Images
1. **hero-roof.jpg** - Main hero image (high-quality roofing work)
   - Recommended size: 1920x1080px or larger
   - High resolution, professional roofing shot

### Service Images
2. **service-roofing.jpg** - General roofing services (800x600px)
3. **service-repairs.jpg** - Roof repair work (800x600px)
4. **service-flat-roof.jpg** - Flat roofing work (800x600px)
5. **service-guttering.jpg** - Guttering/fascias work (800x600px)
6. **service-chimney.jpg** - Chimney repair work (800x600px)

### Image Guidelines
- Use high-quality, professional photos
- Consistent style and lighting
- Show completed work/quality craftsmanship
- Before/after shots work well
- Include Cardiff/Bristol area imagery where possible

## 🚀 Getting Started

### Simple Setup (No Server Required)

1. Simply open `index.html` in any modern web browser
2. All pages are linked and will work locally

### With Local Server (Recommended)

Using Python (Python 3):
```bash
cd "Total Roof Care"
python3 -m http.server 8000
```

Then visit: `http://localhost:8000`

Using Node.js (with npx):
```bash
cd "Total Roof Care"
npx http-server -p 8000
```

Using VS Code:
- Install "Live Server" extension
- Right-click `index.html` and select "Open with Live Server"

## ✨ Features

### Homepage
- Hero section with Checkatrade badge
- About section with personal story
- 6 key feature highlights
- Main services showcase (5 services)
- Comprehensive services checklist (70+ services)
- 5 customer testimonials
- "Why Choose Us" section
- Service area map
- Call-to-action banner

### Contact Page
- Contact information display
- Free quote request form
- Service area coverage map
- Areas covered list
- Trust badges and verification

### Portfolio Page
- Coming soon placeholder
- Testimonials preview
- Trust badges
- Call-to-action for direct contact

### Interactive Features
- Mobile responsive navigation
- Smooth scroll animations
- Scroll-to-top button
- Form validation
- Cookie consent banner (GDPR)
- Lazy image loading
- Interactive hover effects

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Laptop (1024px+)
- Tablet (768px+)
- Mobile (480px+)
- Small mobile (320px+)

## 🔧 Customization

### Update Contact Information

Edit the phone numbers and email in:
- `index.html` (multiple locations)
- `contact.html` (multiple locations)
- `portfolio.html` (multiple locations)

Search for: `07476 968266` and update as needed.

### Update Service Areas

Edit service areas in:
- Footer sections (all pages)
- Service area sections
- Contact page areas list

### Modify Colors

All colors are defined as CSS variables in `css/styles.css`:

```css
:root {
    --primary-blue: #1E3A8A;
    --accent-gold: #D4A853;
    /* ... other colors ... */
}
```

Change these values to update colors throughout the site.

### Update Content

All content is in HTML files - simply edit the text directly:
- `index.html` - Homepage content
- `contact.html` - Contact page content
- `portfolio.html` - Portfolio page content

## 📧 Contact Form Setup

The contact form currently shows a success message without sending emails. To make it functional:

### Option 1: Formspree (Easy, Free)
1. Sign up at [Formspree.io](https://formspree.io)
2. Create a form and get your form endpoint
3. Update the form action in `contact.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS (Free tier available)
1. Sign up at [EmailJS.com](https://www.emailjs.com)
2. Follow their setup guide
3. Update `js/script.js` with EmailJS code

### Option 3: Backend Server
- Set up a backend server (PHP, Node.js, etc.)
- Create an email handling endpoint
- Update form submission in `js/script.js`

## 🗺️ Google Maps

The map is currently using a placeholder embed. To add a working map:

1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your business location
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the iframe in:
   - `index.html` (service area section)
   - `contact.html` (map section)

## 🔍 SEO Optimization

The site includes:
- Meta descriptions
- Keywords
- Semantic HTML structure
- Alt tags for images (add when uploading images)
- Fast loading optimized code

### To Further Optimize:
1. Add a `robots.txt` file
2. Create a `sitemap.xml`
3. Add structured data (Schema.org)
4. Optimize images (compress before uploading)
5. Consider adding a blog section

## ✅ Checklist Before Launch

- [ ] Add all required images
- [ ] Update email address throughout site
- [ ] Test contact form functionality
- [ ] Update Google Maps embed
- [ ] Test on all devices/browsers
- [ ] Check all links work
- [ ] Add favicon.ico
- [ ] Set up form handling (Formspree/EmailJS)
- [ ] Test phone number links on mobile
- [ ] Add Google Analytics (optional)
- [ ] Set up SSL certificate (HTTPS)
- [ ] Add privacy policy page
- [ ] Test loading speed
- [ ] Final content proofread

## 🌐 Deployment

### Option 1: Netlify (Recommended)
1. Sign up at [Netlify.com](https://www.netlify.com)
2. Drag and drop the entire folder
3. Get your live URL
4. Free SSL included

### Option 2: GitHub Pages
1. Create GitHub repository
2. Push files to repository
3. Enable GitHub Pages in settings
4. Access at username.github.io/repo-name

### Option 3: Traditional Hosting
1. Purchase hosting (SiteGround, Bluehost, etc.)
2. Upload files via FTP
3. Point domain to hosting

## 📞 Support & Contact

**Business Contact:**
- Phone: 07476 968266
- Based in: Highbridge, Somerset
- Serving: Cardiff, Bristol & Surrounding Areas

## 📄 License

This website is created for Total Roof Care. All rights reserved.

---

**Built with:** HTML5, CSS3, JavaScript
**Design inspired by:** CaSA Architects template
**Status:** Ready for deployment (after images added)

