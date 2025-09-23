CodeChallenge – Skincare Landing Page

A modern and responsive landing page for a men's skincare product line.
Built with HTML5, SCSS (compiled to CSS), and the Foundation framework, the project emphasizes accessibility, responsiveness, and clean UI/UX design.

🌐 Live Demo

codechallenge-xi.vercel.app

🌟 Overview

This landing page features:

A top announcement bar for promotions

A responsive navbar with a logo, call-to-action button, and cart

An off-canvas menu for mobile navigation

A hero section with headline, call-to-action, and testimonial

A feature section showcasing benefits with text and imagery

A second section with quick highlights using icons and short text

The design is optimized for mobile-first development while ensuring accessibility compliance (ARIA labels, focus states, semantic HTML).



🧩 Tech Stack

HTML5 – Semantic markup

SCSS – Modular styles compiled into CSS

Foundation Sites – Responsive grid & UI framework

jQuery – Required by Foundation

What Input – Input method detection

Google Fonts – Inter, Roboto Mono

📂 Project Structure
├── css/
│   └── app.css         # Compiled stylesheet (from SCSS)
├── images/             # Logo, product images, icons
├── js/                 # Custom scripts (if needed)
├── index.html          # Main HTML file
└── README.md           # Documentation

🛠 Installation

Clone the repository:

git clone https://github.com/ronnelsantos08/codechallenge.git
cd codechallenge


Install dependencies (if any) and run locally:

npx live-server


Open your browser at http://localhost:8080.

📱 Responsive Design

Desktop ≥1024px – Full navbar, hero side-by-side layout, grid-based features

Tablet ≤768px – Navbar compresses, stacked hero section, flexible grids

Mobile ≤480px – Off-canvas menu, stacked content, simplified design

♿ Accessibility

ARIA labels added to custom buttons (hamburger, close menu)

Keyboard navigable controls with visible focus states

Logical tab order matches visual layout

Off-canvas menu hidden from assistive tech when not active

HTML landmarks (nav, main, section) improve screen reader navigation

lang="en" set on <html> tag

🔧 Customization

Colors & Fonts → Edit app.scss

Images → Replace assets in /images/

CTA text → Update in index.html

✅ Future Improvements

Add form integration (newsletter signup, contact form)

Implement basic animations for hero and feature sections

Improve off-canvas menu accessibility (focus trapping)

Optimize images with lazy loading and WebP format

👨‍💻 Author

Ronnel Santos
Front-End & UI/UX Developer
📍 Cavite, Philippines
🌐 Portfolio: ronnelsantos.vercel.app

💻 GitHub: @ronnelsantos08

📜 License

This project is open source and available under the MIT License.
You are free to use, modify, and distribute with attribution.
