# Simplotel Frontend Assignment

## Project Overview

A responsive, production-ready frontend webpage built with semantic HTML5 and vanilla CSS3. The project demonstrates modern web development practices including responsive design, accessibility considerations, and clean code architecture. The implementation features a fully functional navigation system, dynamic mobile menu, and optimized image gallery layout across all device sizes.

## Technology Stack

- **HTML5:** Semantic markup with proper document structure (`<nav>`, `<header>`, `<main>`, `<section>`)
- **CSS3:** Modern layout techniques including Flexbox for navigation and CSS Grid for gallery layout
- **Vanilla JavaScript:** Lightweight (minimal footprint) implementation for interactive menu toggle functionality

## Key Features

### ✅ Responsive Design
- Fully responsive across Desktop, Tablet, and Mobile breakpoints
- Optimized viewport meta tags for proper mobile rendering
- Flexible layouts using Flexbox and Grid for maintainability

### ✅ Navigation System
- Semantic HTML navigation structure
- Responsive hamburger menu for mobile devices
- Smooth toggle functionality for enhanced user experience
- Proper ARIA attributes consideration for accessibility

### ✅ Image Gallery
- CSS Grid-based layout for scalable gallery presentation
- `object-fit: cover` implementation for consistent image aspect ratios
- Responsive image sizing without distortion across devices

### ✅ Design & UX
- Clean, professional design following provided mockups
- Consistent color scheme and typography hierarchy
- Optimized for readability and user engagement

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation & Usage
```bash
# Clone the repository
git clone https://github.com/NarahariAbhinav/Simplotel-Assignment.git

# Open in browser
cd simplotel-frontend-assignment
# Simply open index.html in your browser
```

No npm install or build process required—the project uses vanilla HTML/CSS/JavaScript.

## Project Structure

```
simplotel-frontend-assignment/
├── index.html          # Main HTML document with semantic structure
├── css/
│   └── style.css       # Stylesheet with responsive breakpoints
├── images/             # Project assets (optimized images)
└── README.md          # Project documentation
```

## Technical Highlights

### Code Quality
- **Semantic HTML:** Proper use of semantic tags for better accessibility and SEO
- **Mobile-First Approach:** CSS written for mobile, enhanced for larger screens
- **Maintainable CSS:** Organized stylesheet with clear sections and comments
- **No Dependencies:** Pure vanilla HTML/CSS/JavaScript—lightweight and fast

### Performance Considerations
- Minimal JavaScript for fast load times and reduced dependencies
- Optimized image handling with `object-fit` property
- Efficient CSS selectors and layout optimization
- No external frameworks or libraries

### Responsive Breakpoints
- **Mobile:** < 768px
- **Tablet:** 768px - 1024px  
- **Desktop:** > 1024px

## Browser Compatibility

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Design Decisions

### Architecture
- **Plain CSS Approach:** Avoided pre-processors (SASS/LESS) to maintain simplicity and follow vanilla CSS best practices
- **Vanilla JavaScript:** Minimal, efficient code for menu toggle—no jQuery or frameworks
- **Semantic Markup:** Proper HTML structure for accessibility and SEO benefits

### Implementation Details
- Image aspect ratios maintained using CSS Grid and `object-fit` properties
- Mobile hamburger menu implemented with pure CSS toggle and JavaScript event handling
- Flexible, maintainable class naming conventions for scalability

## Future Enhancement Opportunities

- CSS Custom Properties (CSS Variables) for theme customization
- Progressive enhancement with lazy loading for images
- Animation transitions for improved user experience
- Dark mode implementation
- Accessibility enhancements (WCAG 2.1 AA compliance audit)

## Verification & Testing

The project has been tested and verified to:
- ✅ Render correctly across all major browsers
- ✅ Display responsively on mobile, tablet, and desktop devices
- ✅ Function properly with JavaScript disabled (graceful degradation)
- ✅ Match provided design specifications and mockups

## Author

**Abhinav Narahari**  
BTech Final Year, Nmims

## License

This project is part of an academic assignment and is provided as-is for educational purposes.