Product Designer Portfolio — Responsive Single-File Website Template

A pixel-perfect, fully responsive portfolio template built for Product Designers, UX/UI Specialists, and Creative Creatives.
This project converts a high-fidelity Figma design into a single-file, production-ready HTML implementation using Tailwind CSS.

🚀 Overview
Design

Dark theme with strong visual hierarchy

Modern typography: Space Grotesk & Inter

Soft gradients and vibrant brand accents

Tech Stack

HTML5

Tailwind CSS (via CDN)

FontAwesome for icons

Responsiveness

Fully responsive layout optimized for:

Mobile

Tablet

Desktop

Performance

Zero external JavaScript dependencies

CSS-only mobile menu

Lightweight, fast loading

✨ Features
🔹 Single-File Architecture

Everything (HTML, Tailwind config, minimal script) is inside one index.html for easy portability and deployment.

🔹 CSS-Only Mobile Navigation

Uses the checkbox hack to toggle the mobile menu without JavaScript.

🔹 Custom Tailwind Theme

Embedded Tailwind configuration with:

Custom brand colors (brand-pink, brand-purple, brand-yellow)

Custom fonts (Space Grotesk + Inter)

Utility extensions

🔹 Interactive Elements

Hover animations for buttons & cards

Smooth scrolling

Animated stats section

🔹 Responsive Portfolio Grid

1 Column → Mobile

2 Columns → Tablet

4 Columns → Desktop

🛠️ Setup & Usage

Because this project uses Tailwind via CDN, no build process (npm/CLI) is required.

1. Download

Save index.html from the repository to your device.

2. Run Locally

Simply open the file in any browser:

Chrome

Firefox

Edge

Safari

3. Deploy Anywhere

Upload index.html to any static hosting provider:

Netlify (Drop)

GitHub Pages

Vercel

Firebase Hosting

Standard FTP hosting

⚠️ For production-scale apps, switch to Tailwind CLI to purge unused CSS and optimize performance.

🎨 Customization

All Tailwind config and color/theme settings are inside the <script> block in <head>.

Change Colors

Modify inside tailwind.config:

colors: {
  dark: '#050505',
  'brand-purple': '#8A4FFF',
  // Update or add brand colors here
}

Change Fonts

Update the Google Fonts <link> in the <head>.

Adjust font families:

fontFamily: {
  sans: ['Inter', 'sans-serif'],
  display: ['Space Grotesk', 'sans-serif'],
}

Modify Images

Replace portfolio background images (Unsplash placeholders).

Update hero/footer images via <img src="...">.

📱 Accessibility

Designed with A11Y best practices:

Semantic HTML5 tags

ARIA labels for toggles

Keyboard-friendly focus states

High-contrast text

📄 License

This project is open-source and free for:

Personal portfolios

Commercial use

Client projects

No attribution required — just build and create!