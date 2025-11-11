# Quick Acc Financial Solutions

A modern, professional website for Quick Acc Financial Solutions - a premier audit and accounting firm providing comprehensive financial services.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Animated Background**: Dynamic particle animation for enhanced visual appeal
- **Smooth Scrolling**: Seamless navigation between sections with smooth scroll behavior
- **Scroll Reveal Animations**: Content elegantly reveals as users scroll through the page
- **Mobile Navigation**: Collapsible hamburger menu for mobile devices
- **Professional Styling**: Modern glassmorphism effects with gradient accents
- **Contact Information**: Easy-to-access contact details with clickable phone and email links

## 📋 Sections

1. **Home/Hero**: Eye-catching introduction with call-to-action buttons
2. **About Us**: Comprehensive overview of the firm's mission and values
3. **Services**: Detailed breakdown of four service categories:
   - Bookkeeping & Accounting
   - Financial Reporting & Reconciliation
   - Compliance & Regulatory Services
   - System Implementation & Advisory
4. **Team**: Profiles of key team members
5. **Testimonials**: Client feedback and reviews
6. **Contact**: Multiple contact methods with business hours and location

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties, flexbox, and grid
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome 6.4.0**: Icon library for visual elements

## 📁 File Structure

```
project/
│
├── index.html          # Main HTML file
├── assets/
│   ├── style.css       # Stylesheet with all styling
│   ├── qa_logo.png     # Company logo
│   └── background.jpg  # Background image used in .bg-animation
└── README.md           # This file
```
```

## 🎨 Color Scheme

The website uses a professional blue gradient theme:

- **Primary Color**: `#2E3093` (Deep Blue)
- **Primary Dark**: `#1e3a8a` (Navy Blue)
- **Accent Color**: `#4f46e5` (Indigo)
- **Background Dark**: `#1a1a2e` (Dark Blue-Gray)
- **Background Darker**: `#16213e` (Deeper Blue-Gray)

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic text editor or IDE
- Web server (optional, for local development)

### Installation

1. Clone or download the repository
2. Ensure the file structure is maintained
3. Place your logo image in the `assets/` folder as `qa_logo.png`
4. Open `index.html` in your web browser

### Customization

#### Changing Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #2E3093;
    --primary-dark: #1e3a8a;
    --accent-color: #4f46e5;
    --bg-dark: #1a1a2e;
    --bg-darker: #16213e;
}
```

#### Adding Background Image

In `style.css`, modify the `.bg-animation` class:

```css
.bg-animation::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('your-image-path.jpg');
    background-size: cover;
    background-position: center;
    opacity: 0.1;
}
```

#### Updating Content

- Edit text content directly in `index.html`
- Update contact information in the contact section
- Modify service lists and descriptions as needed

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Mobile**: ≤ 768px

The navigation automatically switches to a hamburger menu on mobile devices.

## ✨ Key Features Explained

### Scroll Reveal Animation

Elements with the class `.scroll-reveal` fade in and slide up as they enter the viewport:

```javascript
function revealOnScroll() {
    const reveals = document.querySelectorAll('.scroll-reveal');
    reveals.forEach(element => {
        const elementTop = element.getBoundingClientRect().top;
        const elementVisible = 150;
        if (elementTop < window.innerHeight - elementVisible) {
            element.classList.add('active');
        }
    });
}
```

### Animated Background

Dynamic particle animation created with JavaScript generates 50 floating particles across the background.

### Mobile Menu

Toggle functionality allows smooth opening/closing of the mobile navigation menu with proper animation states.

## 📞 Contact Information

- **Phone**: 070 2691684
- **Email**: 
  - sanjayahaduwala@gmail.com
  - subash.arawinda@gmail.com
- **Business Hours**: Monday - Friday, 8:30 AM - 5:00 PM
- **Location**: Colombo, Sri Lanka

## 👥 Team

- **Samantha Sanjaya Handuwala** - Founder & Principal Consultant
- **Subash Arawinda** - Senior Financial Consultant

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

© 2025 Quick Acc Financial Solutions. All rights reserved.

## 🤝 Contributing

This is a private business website. For inquiries about updates or modifications, please contact the website administrator.

## 📝 Notes

- Ensure all images are optimized for web performance
- Test responsiveness on multiple devices before deployment
- Keep contact information up to date
- Regularly update testimonials and service offerings

## 🆘 Support

For technical support or questions about the website, please contact the development team or refer to the contact information provided above.

---

**Built with dedication for Quick Acc Financial Solutions**