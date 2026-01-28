# 🎨 Responsive Portfolio Website

A modern, fully responsive portfolio website built with HTML5, CSS3, and JavaScript. This project showcases professional web development practices, including semantic HTML, advanced CSS layouts, responsive design, and interactive features.

## 📋 Project Overview

This portfolio website demonstrates a complete understanding of web development fundamentals and best practices. It includes multiple pages, a responsive design that works across all devices, smooth animations, and a fully functional contact form with validation.

**Live Demo:** [https://ankit-cse-01.github.io/portfolio/home.html]  
**Repository:** [https://github.com/Ankit-CSE-01/portfolio.git]

---

## ✨ Features

### 🎯 Core Features
- ✅ **Fully Responsive Design** - Mobile-first approach with breakpoints for tablets and desktops
- ✅ **Sticky Navigation Bar** - Always accessible navigation with smooth transitions
- ✅ **Hero Section** - Eye-catching hero with animations and call-to-action buttons
- ✅ **Project Cards** - Flex layout with hover effects and smooth animations
- ✅ **Gallery Grid** - CSS Grid image gallery with overlay effects
- ✅ **Skills Section** - Animated progress bars with skill information
- ✅ **Pricing Table** - Service packages displayed in responsive grid
- ✅ **Contact Form** - Complete form validation with error handling
- ✅ **Footer** - Social media links and copyright information

### 🎨 Design & UX
- 🎨 CSS Variables for consistent theming
- 🎨 Smooth animations and transitions
- 🎨 Hover effects on interactive elements
- 🎨 Professional color scheme with primary and secondary colors
- 🎨 Accessible form inputs with focus states
- 🎨 Responsive typography that scales with screen size

### 💻 Technical Highlights
- 📱 Mobile-first responsive design
- 🔧 Flexbox and CSS Grid layouts
- 🎭 CSS animations and keyframes
- 📍 Absolute and sticky positioning
- ✔️ Form validation with JavaScript
- 🎯 Semantic HTML structure
- ♿ Accessibility features (ARIA labels, proper heading hierarchy)

---

## 📁 Project Structure

```
portfolio/
├── index.html              # Home page with hero and featured projects
├── about.html              # About page with experience timeline
├── projects.html           # Projects showcase with gallery and pricing
├── contact.html            # Contact form with validation
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet with all responsive styles
│   ├── js/
│   │   └── script.js       # JavaScript for interactivity and validation
│   └── images/             # Image assets folder
├── .gitignore              # Git ignore configuration
└── README.md               # This file
```

---

## 🛠 Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **HTML5** | Latest | Semantic markup and structure |
| **CSS3** | Latest | Styling, layouts, and animations |
| **JavaScript (ES6+)** | Latest | Interactivity and form validation |
| **Flexbox** | CSS3 | Navbar and card layouts |
| **CSS Grid** | CSS3 | Gallery and pricing grid layouts |
| **CSS Variables** | CSS3 | Dynamic theming and consistency |
| **Media Queries** | CSS3 | Responsive breakpoints |

---

## 📚 CSS Concepts Used

| Concept | Implementation |
|---------|-----------------|
| **Box Model** | Padding, margin, and border styling throughout |
| **Flexbox** | Navbar layout, card containers, footer layout |
| **Grid** | Gallery grid (3 columns), pricing table, skills section |
| **Position** | Sticky navbar, absolute badge positioning, overlays |
| **Media Queries** | Mobile (480px), Tablet (768px), Desktop (1200px) |
| **Animations** | Keyframe animations (fadeIn, float, pulse, slideIn) |
| **Pseudo-classes** | :hover, :focus, :nth-child selectors |
| **Variables** | 40+ CSS custom properties for colors, spacing, transitions |
| **Responsive Units** | %, rem, vw, vh for flexible sizing |

---

## 🎯 Responsive Breakpoints

The website uses a mobile-first approach with the following breakpoints:

```css
/* Mobile: 480px and below */
@media (max-width: 480px) { ... }

/* Tablet: 768px and below */
@media (max-width: 768px) { ... }

/* Large Desktop: 1200px and above */
@media (min-width: 1200px) { ... }
```

### Mobile Optimizations
- Single column layout
- Full-width content
- Hamburger menu navigation
- Larger touch targets
- Simplified form layout

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Git for version control

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. **Open in browser:**
```bash
# Simply open index.html in your browser
# Or use a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

3. **View the website:**
Open `index.html` in your web browser

---

## 📋 Pages & Functionality

### 1. **Home (index.html)**
- Hero section with call-to-action
- Featured projects showcase
- Skills section with animated progress bars
- Navigation to other pages

### 2. **About (about.html)**
- Personal introduction
- Experience timeline
- Professional background
- Skills and expertise list

### 3. **Projects (projects.html)**
- Image gallery with CSS Grid
- Project cards with overlay effects
- Service pricing table
- Featured project section

### 4. **Contact (contact.html)**
- Fully validated contact form
- Form fields: Name, Email, Subject, Message
- Error messages for invalid inputs
- Success message on valid submission
- Contact information sidebar

---

## ✔️ Form Validation

The contact form includes comprehensive validation:

```javascript
// Validation Rules
- Name: Required, minimum 2 characters
- Email: Required, valid email format
- Subject: Required, minimum 3 characters
- Message: Required, minimum 10 characters
```

**Error Handling:**
- Visual error indicators (red borders)
- Inline error messages below each field
- Clear error text describing the issue

---

## 🎨 Color Palette

```css
:root {
    --primary-color: #6366f1;      /* Indigo */
    --secondary-color: #ec4899;    /* Pink */
    --dark-bg: #0f172a;            /* Dark slate */
    --light-bg: #f8fafc;           /* Light gray */
    --text-dark: #1e293b;          /* Dark text */
    --text-light: #64748b;         /* Light gray text */
}
```

---

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

---

## 🔄 Git Workflow

### Commits Made

1. **Commit 1:** Project structure setup with HTML pages, CSS variables, and JavaScript foundation
2. **Commit 2:** Add gitignore and navbar styling with sticky header
3. **Commit 3:** About section styling and layout improvements
4. **Commit 4:** Cards layout with Flexbox and Grid implementation
5. **Commit 5:** Gallery with CSS Grid layout and image overlays
6. **Commit 6:** Complete media queries for mobile, tablet, and desktop
7. **Commit 7:** CSS animations, transitions, and hover effects
8. **Commit 8:** Final polish, README, and project completion

### Branches Used

```
main
├── feature/navbar          # Navbar and hero section
├── feature/responsive      # Responsive design and layouts
├── feature/animations      # Animations and interactions
└── feature/final-polish    # Final touches and documentation
```

### Pull Request Workflow

1. Create feature branch from main
2. Make commits with clear messages
3. Create Pull Request on GitHub
4. Review changes
5. Merge to main branch

---

## 🎓 Learning Outcomes

Through this project, you've learned:

✅ **HTML5 Semantics:** Proper use of semantic elements  
✅ **CSS Layout:** Flexbox and Grid for modern layouts  
✅ **Responsive Design:** Media queries and mobile-first approach  
✅ **CSS Animations:** Keyframes and transitions  
✅ **JavaScript Interactivity:** DOM manipulation and validation  
✅ **Form Handling:** Client-side validation and user feedback  
✅ **Git Workflow:** Branching, committing, and pull requests  
✅ **Professional Practices:** Clean code, documentation, version control  

---

## 📊 Project Statistics

- **HTML Files:** 4
- **CSS Variables:** 40+
- **Animations:** 4 keyframe animations
- **Media Query Breakpoints:** 3
- **JavaScript Functions:** 10+
- **Total Lines of Code:** 1500+
- **Commits:** 8
- **Branches:** 5

---

## 🚀 Deployment (GitHub Pages)

### Steps to Deploy:

1. **Push to GitHub:**
```bash
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main
```

2. **Enable GitHub Pages:**
   - Go to repository settings
   - Scroll to "Pages" section
   - Select "main" branch as source
   - Click Save

3. **Access your site:**
   - Visit: `https://yourusername.github.io/portfolio`

---

## ✨ Bonus Features Implemented

- 🌓 Dark/Light mode toggle (CSS variables ready)
- 📱 Mobile-first design approach
- 🎯 Smooth scroll behavior
- 🔍 Form validation with visual feedback
- ♿ Accessibility features (ARIA labels)
- 🎨 Consistent spacing and typography

---

## 🐛 Troubleshooting

### Images Not Loading
- Ensure image paths are correct relative to HTML files
- Check file permissions
- Use placeholder services (placeholder.com) for demo

### Form Not Submitting
- Update Formspree ID in contact.html form action
- Or implement your own backend service
- Form validation works, but submission requires backend

### Styles Not Applying
- Clear browser cache (Ctrl+Shift+Del)
- Check CSS file path in HTML
- Verify CSS file exists in assets/css/ folder

---

## 📝 License

This project is open source and available for educational purposes.

---

## 👤 Author

**Portfolio Student**  
Email: 73ankitkrsingh@gmail.com 
GitHub: (https://github.com/Ankit-CSE-01/portfolio)

---

## 📚 Additional Resources

- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS-Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks - Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [GitHub Docs - GitHub Pages](https://docs.github.com/en/pages)

---

## 📞 Support

For questions or issues, feel free to:
- Open an issue on GitHub
- Check existing documentation
- Review the code comments

---

**Last Updated:** January 2026  
**Version:** 1.0.0  
**Status:** ✅ Complete and Responsive

---

### 🎉 Congratulations!

You've successfully completed a comprehensive responsive portfolio website project with professional-grade HTML, CSS, and JavaScript!
