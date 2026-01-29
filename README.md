# Manish Kumar Mahato | Portfolio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat&logo=fontawesome&logoColor=white)](https://fontawesome.com/)

A modern, responsive personal portfolio website showcasing skills, education, projects, and professional information for Manish Kumar Mahato, a B.Tech CSE (Data Science) student and aspiring web developer.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Sections](#sections)
- [Customization Guide](#customization-guide)
- [Responsive Design](#responsive-design)
- [Browser Compatibility](#browser-compatibility)
- [Performance Optimization](#performance-optimization)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

This portfolio website serves as a comprehensive digital presence for showcasing professional skills, academic achievements, and project work. Built with modern web technologies, it features a clean, intuitive design with smooth animations and full responsiveness across all devices.

## Features

- **📱 Fully Responsive Design**: Seamlessly adapts to desktop, tablet, and mobile devices
- **🎨 Modern UI/UX**: Clean, professional interface with smooth animations and transitions
- **🔍 Easy Navigation**: Fixed header with smooth scroll navigation to all sections
- **💼 Project Showcase**: Dedicated section highlighting key projects with descriptions
- **🎓 Education Timeline**: Visual timeline displaying academic journey
- **💻 Skills Display**: Interactive skill cards with hover effects
- **📧 Contact Form**: Functional contact form with form validation
- **🔗 Social Integration**: Direct links to LinkedIn, GitHub, Twitter, and Instagram
- **📄 Downloadable CV**: One-click access to downloadable resume
- **⚡ Fast Loading**: Optimized assets for quick page load times
- **🌙 Smooth Animations**: CSS animations for enhanced user experience

## Demo

Visit the live portfolio: [Manish Kumar Mahato Portfolio](https://codebymanish-m.github.io/Portfolio/)

## Technologies Used

### Core Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Styling, animations, flexbox, and grid layouts
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation

### External Libraries
- **Font Awesome 6.4.0**: Icon library for visual elements
- **Google Fonts (Poppins)**: Typography

### Design Principles
- Mobile-first responsive design
- CSS Grid and Flexbox for layouts
- CSS custom properties (variables) for theming
- Smooth scroll behavior
- CSS transitions and animations

## Project Structure

```
Portfolio/
├── index.html              # Main HTML file with semantic structure
├── style.css               # Complete styling with animations
├── script.js               # JavaScript for interactivity
├── photo.jpeg              # Profile image
├── README.md               # Project documentation
└── assets/                 # (Optional) Additional assets folder
    ├── images/
    ├── documents/
    │   └── CV.pdf
    └── icons/
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, Atom) for customization
- Basic understanding of HTML/CSS/JavaScript (for modifications)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CodebyManish-M/Portfolio.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Portfolio
   ```

3. **Open in browser**:
   ```bash
   # On Windows
   start index.html
   
   # On macOS
   open index.html
   
   # On Linux
   xdg-open index.html
   ```

### Alternative: Using Live Server

For development with auto-reload:

1. **Install Live Server** (VS Code extension or npm package):
   ```bash
   npm install -g live-server
   ```

2. **Run the server**:
   ```bash
   live-server
   ```

3. **Access at**: `http://127.0.0.1:8080`

## Sections

### 1. Header & Navigation
- Fixed navigation bar with logo
- Responsive hamburger menu for mobile
- Smooth scroll to sections
- Active link highlighting

### 2. Hero Section
- Professional introduction
- Profile image with styling
- Call-to-action button
- Gradient background

### 3. About Me
- Personal introduction and bio
- Key information display:
  - Name
  - Email
  - Age
  - Location
- Downloadable CV button
- Professional description

### 4. Skills
- Interactive skill cards with icons:
  - HTML5
  - CSS3
  - JavaScript
  - React
  - Python
  - MySQL
- Hover effects and animations
- Skill descriptions

### 5. Education
- Visual timeline design
- Academic progression:
  - B.Tech in CSE (Data Science)
  - Intermediate Education
  - High School
- Chronological layout

### 6. Projects
- Project cards with:
  - Project icons
  - Titles and descriptions
  - View project links
- Featured projects:
  - E-Commerce Website
  - Data Analysis Tool
  - Weather App
- Hover animations

### 7. Contact
- Contact information:
  - Email: manishmahato2027@gmail.com
  - Phone: +91 9142928815
  - Location: Jharkhand, India
- Functional contact form with fields:
  - Name
  - Email
  - Subject
  - Message
- Social media links
- Form validation

### 8. Footer
- Copyright information
- Social media links
- Consistent design

## Customization Guide

### Changing Colors

Edit the CSS custom properties in `style.css`:

```css
:root {
    --primary-color: #4a6cf7;      /* Main brand color */
    --secondary-color: #6f42c1;    /* Accent color */
    --dark-color: #1d2144;         /* Dark text/backgrounds */
    --light-color: #f8f9fa;        /* Light backgrounds */
    --text-color: #333;            /* Primary text */
    --text-light: #666;            /* Secondary text */
}
```

### Updating Personal Information

1. **Profile Image**: Replace `photo.jpeg` with your image (recommended: 400x500px)

2. **Personal Details**: Edit `index.html`:
   ```html
   <h1>Hi, I'm <span>Your Name</span></h1>
   <p>Your bio and introduction...</p>
   ```

3. **Contact Information**: Update email, phone, and location in the contact section

4. **Social Links**: Replace URLs in footer and contact sections:
   ```html
   <a href="https://www.linkedin.com/in/your-profile/"><i class="fab fa-linkedin-in"></i></a>
   ```

### Adding New Skills

In `index.html`, add a new skill card:

```html
<div class="skill-card">
    <i class="fab fa-node-js"></i>
    <h3>Node.js</h3>
    <p>Server-side JavaScript runtime for building scalable applications.</p>
</div>
```

### Modifying Projects

Update project information in the projects section:

```html
<div class="project-card">
    <div class="project-img">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description and technologies used.</p>
        <a href="your-project-url" class="btn">View Project</a>
    </div>
</div>
```

### Updating CV Link

Replace the Google Drive link with your CV URL:

```html
<a href="your-cv-link" class="btn">Download CV</a>
```

### Customizing Animations

Modify animation delays and durations in `script.js`:

```javascript
card.style.animationDelay = `${index * 0.2}s`; // Adjust delay
```

Add custom animations in `style.css`:

```css
@keyframes yourAnimation {
    from { /* starting state */ }
    to { /* ending state */ }
}
```

## Responsive Design

### Breakpoints

- **Desktop**: > 992px (full layout)
- **Tablet**: 768px - 992px (adjusted columns)
- **Mobile**: < 768px (stacked layout, hamburger menu)

### Mobile Optimizations

- Hamburger menu for navigation
- Stacked sections for better readability
- Touch-friendly button sizes
- Optimized image sizes
- Single-column layouts

### Testing Responsive Design

Test on various devices:
```bash
# Chrome DevTools: F12 → Toggle Device Toolbar
# Test on: iPhone, iPad, Desktop
```

## Browser Compatibility

| Browser | Minimum Version | Status |
|---------|----------------|---------|
| Chrome | 60+ | ✅ Fully Supported |
| Firefox | 55+ | ✅ Fully Supported |
| Safari | 11+ | ✅ Fully Supported |
| Edge | 79+ | ✅ Fully Supported |
| Opera | 47+ | ✅ Fully Supported |
| IE | 11 | ⚠️ Partial Support |

### Known Issues

- **Internet Explorer**: Limited CSS Grid support (consider using Flexbox fallbacks)
- **Older Browsers**: Some CSS animations may not work

## Performance Optimization

### Current Optimizations

- Minified CSS and JavaScript (for production)
- Optimized images
- Font Awesome CDN for icon delivery
- Smooth scroll without JavaScript libraries
- CSS-based animations (GPU-accelerated)

### Further Optimization Tips

1. **Image Optimization**:
   ```bash
   # Compress images using tools like:
   - TinyPNG
   - ImageOptim
   - Squoosh
   ```

2. **Lazy Loading**:
   ```html
   <img src="image.jpg" loading="lazy" alt="Description">
   ```

3. **Caching**:
   ```html
   <!-- Add cache headers in .htaccess or server config -->
   ```

4. **Minification**:
   ```bash
   # Use tools like:
   npm install -g minify
   minify style.css > style.min.css
   ```

## Future Enhancements

Planned features for future releases:

- [ ] **Dark Mode Toggle**: Theme switcher for light/dark modes
- [ ] **Blog Section**: Share articles and tutorials
- [ ] **Project Filters**: Filter projects by technology/category
- [ ] **Animations Library**: Advanced scroll animations using GSAP
- [ ] **Backend Integration**: Connect contact form to email service
- [ ] **Portfolio CMS**: Easy content management without editing code
- [ ] **Testimonials Section**: Client/peer recommendations
- [ ] **Multi-language Support**: i18n for international visitors
- [ ] **Analytics Integration**: Google Analytics for visitor insights
- [ ] **PWA Features**: Make portfolio installable as app
- [ ] **Accessibility Improvements**: Enhanced ARIA labels and keyboard navigation
- [ ] **Loading Animations**: Skeleton screens and preloaders

## Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add YourFeature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines

- Follow existing code style and formatting
- Test across multiple browsers
- Update documentation for new features
- Keep commits atomic and descriptive
- Add comments for complex logic

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Manish Kumar Mahato

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contact

### Manish Kumar Mahato

- **Email**: [manishmahato2027@gmail.com](mailto:manishmahato2027@gmail.com)
- **Phone**: +91 9142928815
- **Location**: Jharkhand, India

### Connect on Social Media

- **LinkedIn**: [Manish Mahato](https://www.linkedin.com/in/manish-mahato-6bb07029a/)
- **GitHub**: [CodebyManish-M](https://github.com/CodebyManish-Mahato)
- **Twitter**: [@ManishMahat0](https://x.com/ManishMahat0)
- **Instagram**: [@hy._.manish](https://www.instagram.com/hy._.manish/)

## Acknowledgments

- **Font Awesome** for the beautiful icon library
- **Google Fonts** for the Poppins typeface
- **Inspiration** from modern portfolio designs
- **Community** for feedback and support

---

**Made with ❤️ by Manish Kumar Mahato**

© 2025 Manish Kumar Mahato. All Rights Reserved.

---

### Quick Links

- [View Live Portfolio](https://codebymanish-m.github.io/Portfolio/)
- [Report Issues](https://github.com/CodebyManish-M/Portfolio/issues)
- [Download CV](https://drive.google.com/file/d/10RKAcJC6CFMCAcOZXiOuEGbfMw-c-lCH/view)

**⭐ Star this repo if you found it helpful!**
