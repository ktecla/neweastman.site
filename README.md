# Eastman Technical Training Institute

A modern, production-ready, and mobile-responsive website for the Eastman Technical Training Institute in Embu, Kenya.

## Features

- **Semantic HTML5:** Proper structure for accessibility and SEO.
- **Pure CSS3:** Custom properties (CSS variables), Flexbox, and Grid for responsive layouts (no external frameworks like Bootstrap or Tailwind).
- **Vanilla JavaScript:** Smooth scrolling, active navigation highlighting, animated stats counters, mobile menu toggle, and form validation (no external libraries).
- **Mobile Responsive:** Fully responsive across mobile, tablet, and desktop viewports (320px - 1920px).
- **Performance Optimized:** Clean code structure aiming for a Lighthouse score > 80.
- **Accessibility:** ARIA labels, semantic tags, and logical focus management.
- **Design:** Modern Blue and Gold/Orange color scheme with glassmorphism and subtle CSS animations.

## Structure

- `index.html` - The main entry point containing all sections (Home, About, Courses, Admissions, Contact).
- `styles.css` - All styles for the website, including responsive media queries.
- `script.js` - JavaScript logic for interactivity.

## Setup Instructions

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge) to view the site locally.
3. No build tools or Node.js required! This is a static HTML/CSS/JS project.

## Deployment Instructions (Netlify)

This project is ready to be deployed to a static hosting provider like Netlify.

1. Create an account on [Netlify](https://www.netlify.com/).
2. You can deploy in two ways:
   - **Drag and Drop:** Go to your Netlify dashboard under "Sites" and drag the entire project folder into the upload area.
   - **GitHub Integration (Recommended):**
     1. Initialize a Git repository in this folder: `git init`
     2. Commit the files: `git add .` and `git commit -m "Initial commit"`
     3. Push to a new repository on GitHub.
     4. In Netlify, click "Add new site" > "Import an existing project".
     5. Connect to GitHub, select your repository, and click "Deploy site".
3. Netlify will automatically build (no build command needed) and provide you with a live HTTPS URL.
4. (Optional) Set up a custom domain in the Netlify site settings.

## Form Integration

The admissions and contact forms are currently set up with placeholder actions. To make them functional without a backend:

1. Sign up for [Formspree](https://formspree.io/) or [EmailJS](https://www.emailjs.com/).
2. Create a new form endpoint.
3. Replace the `action="https://formspree.io/f/placeholder"` attribute in `index.html` with your actual Formspree endpoint URL.

## Author

Designed and Developed by Antigravity for Eastman Technical Training Institute.
