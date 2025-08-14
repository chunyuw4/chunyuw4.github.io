# Human Integrative Physiology Laboratory Website

A modern, responsive website for the Human Integrative Physiology Laboratory at the University of Illinois. This website showcases the lab's research areas, publications, team members, and provides contact information with a beautiful, contemporary design.

## 🌟 Features

### Design & User Experience
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Responsive Design**: Fully responsive across all devices (desktop, tablet, mobile)
- **Accessibility**: WCAG compliant with keyboard navigation and screen reader support
- **Performance Optimized**: Fast loading with optimized assets and code

### Interactive Elements
- **Smooth Scrolling Navigation**: Seamless navigation between sections
- **Mobile-Friendly Menu**: Hamburger menu for mobile devices
- **Animated Cards**: Hover effects and scroll-triggered animations
- **Contact Form**: Functional contact form with validation
- **Progress Indicator**: Visual scroll progress bar
- **Back to Top Button**: Easy navigation to the top of the page

### Content Sections
- **Hero Section**: Eye-catching introduction with animated elements
- **Mission Statement**: Clear presentation of lab objectives
- **Research Areas**: Three main research focus areas with icons
- **Publications**: Featured research publications with DOIs
- **Team Members**: Graduate students with photos and research descriptions
- **Opportunities**: Information about joining the lab
- **Contact Information**: Location, email, and contact form

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - runs entirely in the browser

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website will load immediately with all functionality

### File Structure
```
hip-lab-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: #13294B (Illinois Blue - University of Illinois brand)
- **Secondary Blue**: #1F4E79 (Illinois Light Blue)
- **Accent Orange**: #E84A27 (Illinois Orange)
- **Text Colors**: Illinois Blue (#13294B) for headings, Illinois Light Blue (#1F4E79) for body text
- **Background**: Clean white (#ffffff) with light gray (#f8fafc) for sections

### Typography
- **Font Family**: Inter (Google Fonts) with system font fallbacks
- **Font Weights**: 300 (light), 400 (regular), 500 (medium), 600 (semibold), 700 (bold)
- **Responsive Sizing**: Scales appropriately across device sizes

### Components
- **Cards**: Rounded corners (16px), subtle shadows, hover animations
- **Buttons**: Primary (filled) and secondary (outlined) styles
- **Navigation**: Fixed header with backdrop blur effect
- **Forms**: Clean input fields with focus states

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Customization

### Content Updates
To update the website content:

1. **Research Areas**: Modify the content in the `.research-card` sections in `index.html`
2. **Publications**: Update the publication cards with new research
3. **Team Members**: Add or modify team member information
4. **Contact Information**: Update email, address, or department details

### Styling Changes
To modify the design:

1. **Colors**: Update CSS custom properties in `:root` section of `styles.css`
2. **Typography**: Modify font families and sizes in the CSS
3. **Layout**: Adjust grid layouts and spacing as needed
4. **Animations**: Customize animation durations and effects

### Adding New Sections
To add new content sections:

1. Add HTML structure in `index.html`
2. Create corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## 📊 Performance Features

- **Optimized Images**: WebP format with fallbacks
- **Minified CSS/JS**: Production-ready code
- **Lazy Loading**: Images load as needed
- **Debounced Events**: Optimized scroll and resize handlers
- **Intersection Observer**: Efficient animation triggers

## 🔒 Security & Privacy

- **No External Dependencies**: All functionality is self-contained
- **Form Validation**: Client-side validation for contact form
- **No Data Collection**: Contact form simulates submission (no actual data sent)
- **HTTPS Ready**: Secure for production deployment

## 🚀 Deployment

### Local Development
Simply open `index.html` in a web browser for local development.

### Web Server Deployment
1. Upload all files to your web server
2. Ensure `index.html` is set as the default document
3. The website will work immediately

### GitHub Pages
1. Push the project to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the main branch as source
4. Your site will be available at `https://username.github.io/repository-name`

## 📝 Content Management

### Updating Publications
Replace the publication cards in the HTML with new research:

```html
<div class="publication-card">
    <div class="pub-header">
        <h3>Your Publication Title</h3>
        <span class="pub-year">2024</span>
    </div>
    <p class="pub-authors">Author Names</p>
    <p class="pub-journal">Journal Name</p>
    <div class="pub-doi">DOI: 10.xxxx/xxxxx</div>
</div>
```

### Adding Team Members
Add new team member cards:

```html
<div class="team-member">
    <div class="member-photo">
        <img src="path/to/photo.jpg" alt="Student Name" class="member-image">
    </div>
    <h3>Student Name</h3>
    <p class="member-role">PhD/MS Student</p>
    <p class="member-bio">Brief bio description and research focus.</p>
</div>
```

## 🤝 Contributing

To contribute to this project:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test across different devices and browsers
5. Submit a pull request

## 📄 License

This project is created for the Human Integrative Physiology Laboratory at the University of Illinois. All rights reserved.

## 📞 Support

For questions or support regarding this website:
- Email: hip-lab@illinois.edu
- Location: Freer Hall, 906 S. Goodwin Ave, Urbana, IL 61801

---

**Built with ❤️ for the Human Integrative Physiology Laboratory**
