# Portfolio Website

A modern, responsive portfolio website built with HTML and CSS.

## Directory Structure

```
ankit165-wq.github.io/
├── index.html                 # Homepage
├── README.md                  # Documentation
├── assets/
│   └── css/
│       └── style.css         # Main stylesheet (Shared across all pages)
└── pages/
    ├── cv.html              # CV Page
    ├── research.html        # Research Page
    ├── projects.html        # Projects Page
    ├── blog.html            # Blog/Notes Page
    └── contact.html         # Contact Page
```

## Future Navigation Guide

### Adding New Pages
To add a new page to the portfolio:
1. Create a new `.html` file in the `pages/` directory
2. Copy the navigation bar structure from existing pages
3. Update the navigation links to include your new page
4. Link the shared stylesheet: `<link rel="stylesheet" href="../assets/css/style.css">`

### Adding Styles
All CSS styling is located in:
```
assets/css/style.css
```

Modify this file to update colors, fonts, layouts, and responsive design.

### Navigation Bar
The navigation bar contains the following links (in order):
1. **Home** - index.html
2. **CV** - pages/cv.html
3. **Research** - pages/research.html
4. **Projects** - pages/projects.html
5. **Blog/Notes** - pages/blog.html
6. **Contact** - pages/contact.html

## Color Scheme
- Primary Color: #2563eb (Blue)
- Secondary Color: #1e40af (Dark Blue)
- Text Dark: #1f2937 (Dark Gray)
- Text Light: #6b7280 (Light Gray)
- Background Light: #f9fafb (Very Light Gray)
- Background White: #ffffff (White)

## Features
- ✅ Responsive design (Mobile, Tablet, Desktop)
- ✅ Smooth navigation with active page indicator
- ✅ Modern hero section with gradient background
- ✅ Quick links grid
- ✅ Hover animations and transitions
- ✅ Clean and professional styling
