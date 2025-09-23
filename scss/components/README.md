# CodeChallenge – Skincare Landing Page

A modern and responsive **landing page** for a men's skincare product line.  
Built with **HTML5**, **SCSS (compiled to CSS)**, and the **Foundation framework**, the project emphasizes accessibility, responsiveness, and clean UI/UX design.  

---

## 🌐 Live Demo  
👉 [View Project](https://codechallenge-6293lj734-ronnelsantos08s-projects.vercel.app/)  
*(Replace with your Netlify, Vercel, or GitHub Pages link)*  

---

## 🌟 Overview

This landing page features:  
- A **top announcement bar** for promotions  
- A **responsive navbar** with a logo, call-to-action button, and cart  
- An **off-canvas menu** for mobile navigation  
- A **hero section** with headline, call-to-action, and testimonial  
- A **feature section** showcasing benefits with text and imagery  
- A **second section** with quick highlights using icons and short text  

The design is optimized for **mobile-first development** while ensuring accessibility compliance (ARIA labels, focus states, semantic HTML).  

---

## 📸 Preview

![Project Preview](./images/screenshot.png)  
*(Replace with actual screenshot of your project)*  

---

## 🧩 Tech Stack

- **HTML5** – Semantic markup  
- **SCSS** – Modular styles compiled into CSS  
- **Foundation Sites** – Responsive grid & UI framework  
- **jQuery** – Required by Foundation  
- **What Input** – Input method detection  
- **Google Fonts** – *Inter, Roboto Mono*  

---

## 📂 Project Structure


├── css/
│ └── app.css # Compiled stylesheet (from SCSS)
├── images/ # Logo, product images, icons
├── js/ # Custom scripts (if needed)
├── index.html # Main HTML file
└── README.md # Documentation

1. **Clone this repository**
   ```bash
   git clone https://github.com/ronnelsantos08/codechallenge.git
   cd codechallenge

   Install dependencies
   npx live-server

   Navbar

Desktop: shows logo, “Get Started” button, and cart.

Mobile: hamburger button triggers an off-canvas menu.

Hero Section

Includes headline, CTA button, testimonial, and hero image.

Features

Simple routine description with bullet points and icons.

Supporting image for context.

Quick Highlights (Section 2)

Three blocks with icon + text showcasing unique product benefits.

📱 Responsive Design

This project uses a mobile-first approach with SCSS and Foundation’s grid system.

Screen Size	Layout
Desktop ≥1024px	Full navbar, hero side-by-side layout, grid-based features
Tablet ≤768px	Navbar compresses, stacked hero section, flexible grids
Mobile ≤480px	Off-canvas menu, stacked content, simplified design

Accessibility

Accessibility was prioritized during development:

ARIA labels added to custom buttons (hamburger, close menu).

Keyboard navigable controls with visible focus states.

Logical tab order matches the visual order.

Off-canvas menu hidden from assistive tech when not active.

HTML landmarks (<nav>, <main>, <section>) improve screen reader navigation.

lang="en" set on the <html> tag.

Customization

Colors & Fonts → Edit app.scss.

Images → Replace assets in /images/.

CTA text → Update in index.html.

✅ Future Improvements

Add form integration (newsletter signup, contact form).

Implement basic animations for hero and feature sections.

Improve off-canvas menu accessibility (focus trapping).

Optimize images with lazy loading and WebP format.

Author

Ronnel Santos
🎨 Front-End & UI/UX Developer
📍 Cavite, Philippines

🌐 Portfolio: ronnelsantos.vercel.app

💻 GitHub: @ronnelsantos08


License

This project is open source and available under the MIT License.
You are free to use, modify, and distribute with attribution.