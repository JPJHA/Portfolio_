# Jay Prakash Jha - AI Engineer Portfolio

A modern, cinematic portfolio website showcasing AI engineering expertise with stunning 3D animations, glassmorphic design, and a complete dark/light mode system.

## 🚀 Features

### Design System
- **Cinematic Dark Mode** (default) with smooth transitions
- **Pastel Light Mode** toggle with complete theme switching
- **Glassmorphic UI** elements with backdrop blur effects
- **Responsive Design** optimized for all devices
- **Smooth Animations** and micro-interactions

### Sections
1. **Hero Section** - Cinematic 3D intro with floating elements and gradient orbs
2. **About Section** - Animated introduction with skills showcase
3. **Portfolio Section** - Interactive 3D project cards with tilt effects
4. **Experience Section** - Professional timeline with detailed work history
5. **Blogs Section** - Static blog cards with hover animations
6. **Resume Section** - PDF preview with download functionality
7. **Contact Section** - Glassmorphic form with social links

### Interactive Features
- **Theme Toggle** - Switch between dark and light modes
- **Smooth Scrolling** - Navigation with smooth scroll effects
- **3D Tilt Effects** - Interactive portfolio cards
- **Floating Animations** - Hero section floating elements
- **Parallax Effects** - Background elements with depth
- **Form Handling** - Contact form with validation and feedback
- **Mobile Navigation** - Hamburger menu for mobile devices

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Advanced styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Font Awesome** - Icon library
- **Google Fonts** - Inter font family
- **CSS Custom Properties** - Design system variables
- **Intersection Observer API** - Scroll-triggered animations

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS with design system
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization

### Colors and Themes
The website uses CSS custom properties for easy theming. Edit the `:root` variables in `styles.css`:

```css
:root {
  --bg-primary: #0a0a0a;
  --text-primary: #ffffff;
  --accent-primary: #6366f1;
  /* ... more variables */
}
```

### Content Updates
1. **Personal Information**: Update the hero section and about section
2. **Projects**: Modify the portfolio cards in the HTML
3. **Experience**: Update the timeline items with your work history
4. **Blogs**: Replace the blog cards with your actual blog posts
5. **Contact**: Update email, phone, and social media links
6. **Resume**: Replace the PDF placeholder with your actual resume

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Style the section in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update the navigation menu

## 🚀 Getting Started

1. **Clone or Download** the files to your local machine
2. **Open** `index.html` in a web browser
3. **Customize** the content with your information
4. **Deploy** to your preferred hosting platform

### Local Development
```bash
# Simple local server (Python)
python -m http.server 8000

# Or using Node.js
npx serve .

# Or just open index.html in your browser
```

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🎯 Performance Features

- **Optimized Animations** - Hardware-accelerated CSS animations
- **Lazy Loading** - Intersection Observer for performance
- **Responsive Images** - Optimized for different screen sizes
- **Minimal Dependencies** - Only essential external libraries
- **Efficient CSS** - Optimized selectors and properties

## 🔧 Advanced Customization

### Adding New Animations
```javascript
// Add to script.js
function customAnimation() {
    // Your animation code here
}
```

### Modifying the Design System
```css
/* Add new design tokens */
:root {
  --new-color: #your-color;
  --new-spacing: 2rem;
}
```

### Adding New Interactive Elements
```javascript
// Add event listeners for new elements
document.querySelectorAll('.new-element').forEach(el => {
    el.addEventListener('click', handleClick);
});
```

## 📞 Support

For questions or customization help, feel free to reach out!

## 📄 License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Built with ❤️ for Jay Prakash Jha - AI Engineer Portfolio**