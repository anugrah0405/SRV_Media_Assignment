# Three-Page Website Project

A modern, responsive website built with semantic HTML5 and custom CSS, following BEM naming conventions and W3C validation standards.

## 🚀 Features

- **Semantic HTML5**: Proper use of semantic elements for accessibility and SEO
- **BEM CSS Naming**: Block Element Modifier methodology for maintainable CSS
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox
- **W3C Compliant**: Validates against W3C standards
- **Accessibility**: ARIA labels, focus management, and semantic structure
- **Modern CSS**: CSS Grid, Flexbox, custom properties, and smooth transitions

## 📁 Project Structure

```
SRV_Media_Assignment/
├── index.html          # Home page
├── about.html          # About page
├── contact.html        # Contact page
├── css/
│   └── styles.css     # Main stylesheet
└── README.md          # Project documentation
```

## 🎯 Pages Overview

### 1. Home Page (`index.html`)
- Hero section with call-to-action buttons
- Features showcase with hover effects
- Call-to-action section
- Responsive navigation and footer

### 2. About Page (`about.html`)
- Company story and mission
- Mission, vision, and values
- Team member profiles
- Responsive grid layouts

### 3. Contact Page (`contact.html`)
- Contact information with icons
- Interactive contact form
- Business hours and location
- Form validation and accessibility

## 🛠️ Technical Specifications

### HTML5 Features
- Semantic elements (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- Proper heading hierarchy (h1-h6)
- Form elements with proper labels and validation
- Meta tags for SEO and viewport
- ARIA attributes for accessibility

### CSS Features
- **BEM Methodology**: `.block__element--modifier`
- **CSS Grid**: Responsive layouts and card grids
- **Flexbox**: Navigation and component alignment
- **Custom Properties**: Consistent color scheme
- **Media Queries**: Mobile-first responsive design
- **Transitions**: Smooth hover and focus effects

### Accessibility Features
- Proper heading structure
- ARIA labels and roles
- Focus management
- High contrast support
- Reduced motion support
- Semantic HTML structure

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE
- Local web server (optional, for form testing)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate between pages using the navigation menu

### Local Development
For form testing and local development:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 🎨 Customization

### Colors
The color scheme is defined in CSS custom properties and can be easily modified:
- Primary: `#2563eb` (Blue)
- Secondary: `#1e293b` (Dark Blue)
- Accent: `#667eea` to `#764ba2` (Gradient)
- Text: `#333` (Dark Gray)
- Background: `#f8fafc` (Light Gray)

### Typography
- Font Family: Segoe UI, Tahoma, Geneva, Verdana, sans-serif
- Responsive font sizes using rem units
- Proper line heights for readability

### Layout
- Maximum width: 1200px
- Responsive breakpoints: 768px, 480px
- CSS Grid for complex layouts
- Flexbox for component alignment

## 📱 Responsive Design

### Breakpoints
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: 480px to 767px
- **Small Mobile**: Below 480px

### Features
- Mobile-first approach
- Flexible grid systems
- Responsive typography
- Touch-friendly navigation
- Optimized spacing for mobile

## ♿ Accessibility

### Standards Compliance
- WCAG 2.1 AA compliance
- Semantic HTML structure
- Proper ARIA implementation
- Keyboard navigation support
- Screen reader compatibility

### Features
- Focus indicators
- High contrast support
- Reduced motion preferences
- Proper heading hierarchy
- Alt text for images (placeholders)

## 🔍 SEO Features

### Meta Tags
- Proper title tags
- Meta descriptions
- Keywords (for legacy support)
- Author information
- Viewport settings

### Semantic Structure
- Proper heading hierarchy
- Semantic HTML elements
- Descriptive link text
- Structured content

## 🧪 Testing

### Browser Testing
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Validation
- HTML5 validation
- CSS validation
- Accessibility testing
- Cross-browser compatibility

## 📚 BEM Naming Convention

### Structure
```css
.block {}                    /* Block */
.block__element {}          /* Element */
.block--modifier {}         /* Modifier */
.block__element--modifier {} /* Element with modifier */
```

### Examples
```css
.nav {}                     /* Navigation block */
.nav__menu {}              /* Navigation menu element */
.nav__link {}              /* Navigation link element */
.nav__link--active {}      /* Active navigation link */
.btn {}                     /* Button block */
.btn--primary {}           /* Primary button modifier */
.btn--full-width {}        /* Full width button modifier */
```

## 🚀 Performance Features

### Optimizations
- Minimal CSS with no frameworks
- Efficient selectors
- Optimized media queries
- Smooth animations with `transform`
- Minimal DOM manipulation

### Best Practices
- CSS Grid for layouts
- Flexbox for components
- Semantic HTML for better parsing
- Minimal JavaScript dependencies
- Optimized asset loading

## 🤝 Contributing

1. Follow BEM naming conventions
2. Maintain semantic HTML structure
3. Ensure accessibility compliance
4. Test across different browsers
5. Validate HTML and CSS

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

For questions or issues:
- Check the HTML validation
- Verify CSS compliance
- Test accessibility features
- Ensure responsive behavior

## 🔮 Future Enhancements

- JavaScript form validation
- Dark mode toggle
- Animation libraries
- CMS integration
- Performance monitoring
- A/B testing capabilities

---

**Built with ❤️ using semantic HTML5 and modern CSS**
