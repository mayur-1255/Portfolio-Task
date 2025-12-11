Product Designer Portfolio

A pixel-perfect, fully responsive portfolio website template for Product Designers, UX/UI Specialists, and Creative Professionals. This project converts a high-fidelity Figma design into a single-file, production-ready HTML solution using Tailwind CSS.

🚀 Overview

Design: Dark theme, modern typography (Space Grotesk & Inter), and vibrant gradients.

Tech Stack: HTML5, Tailwind CSS (via CDN), FontAwesome.

Responsiveness: Fully adaptive layout covering mobile, tablet, and desktop breakpoints.

Performance: Zero external JavaScript dependencies for UI logic (CSS-only mobile menu).

✨ Features

Single File Architecture: All styles, scripts, and markup are contained in index.html for easy portability.

CSS-Only Mobile Navigation: Uses the "Checkbox Hack" to manage menu state without JavaScript.

Custom Tailwind Configuration: Embedded configuration for brand colors (brand-pink, brand-purple, brand-yellow) and custom fonts.

Interactive Elements:

Hover effects on portfolio cards and buttons.

Smooth scrolling navigation.

Animated stats section.

Responsive Grid:

1 Column (Mobile)

2 Columns (Tablet)

4 Columns (Desktop)

🛠️ Setup & Usage

Since this project uses the Tailwind CSS CDN, no build step (npm/node) is required for development or viewing.

Download: Save the provided index.html file to your computer.

Run: Open the file directly in any modern web browser (Chrome, Firefox, Safari, Edge).

Deploy: Upload this single file to any static hosting provider (Netlify Drop, GitHub Pages, Vercel, or standard FTP).

Note: For a large-scale production app, it is recommended to switch from the CDN script to the Tailwind CLI build process to purge unused styles and improve load times.

🎨 Customization

All styling configurations are located within the <script> tag in the <head> of the document.

Changing Fonts

The project uses Google Fonts. To change them:

Update the <link> tag for Google Fonts in the <head>.

Update the fontFamily section in the tailwind.config.

Updating Images

Portfolio Images: Replace the background-image URLs in the inline styles or Tailwind classes (currently using Unsplash placeholders).

Hero/Footer Images: Update the src attributes of the <img> tags.

📱 Accessibility

Semantic HTML5 tags (<header>, <main>, <article>, <footer>).

ARIA labels on interactive elements (mobile menu toggle).

Focus states for keyboard navigation.

Sufficient color contrast on text elements.

