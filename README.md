# FitCore Studio - Gym Website

Overview
- A complete, production-ready static website for a gym/fitness business using Tailwind CSS (via CDN) with a clean, modern design.
- Built for quick deployment and easy content updates.
- Includes three pages: Home (index.html), About (about.html), and Contact (contact.html).
- Includes a comprehensive footer tailored for a gym, light interactive elements, and a ready-to-edit content structure.

Files
- index.html: Home landing page with hero banner, services grid, call-to-action, and footer.
- about.html: About page with our story and trainer cards.
- contact.html: Contact page with a form and contact details.
- README.md: This file.

Design System Notes
- Category: Gym / Fitness
- Colors: Dark neutral foundation with warm accent (see content in HTML).
- Typography: Primary headings and body text designed to be swapped with category-appropriate fonts via the provided placeholders (e.g., {{font: Oswald}}).
- Layout: Responsive grid, mobile-first, semantic HTML5 sections.

How to Run / Deploy
- Copy the three HTML files to your web server or hosting environment.
- Open index.html in a browser to view the site.
- Fonts: The design expects category-specific font placeholders (e.g., font-[primary-font]). These will be processed by the deployment pipeline to load the requested fonts. If you’re embedding locally, replace placeholders with real font-family declarations or import fonts via a CDN and apply via CSS classes.

Accessibility & SEO
- Semantic HTML5 elements (header, nav, main, section, article, footer).
- All images include descriptive alt attributes.
- Internal navigation links between pages for good UX and SEO.
- Content uses descriptive headings (H1, H2, H3) and concise copy.

Extending / Customizing
- Update text content in each HTML file to reflect your gym’s branding and services.
- Replace image placeholders with real images or your own assets using the provided https://pixabay.com/get/gbe34a9bcdc5879ff5d84844771c242afc3dba3243642dbd222e6e7f6e6b981e4fbd71c87516d032718a72b785d530fc11a522a04d215a2c6a8f4934c35c2f157_640.jpg placeholders.
- If you want more pages (e.g., Classes, Membership, Testimonial), follow the same structure and adjust the navigation accordingly.
