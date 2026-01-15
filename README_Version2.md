# Uttam IT Support — Website Template

This repository contains a modern, enterprise-ready website template for Uttam IT Support. The template is built for performance, accessibility, SEO, and conversion (lead gen).

## Included files
- index.html — Home page (Hero, Services, Products, AMC, Contact CTA)
- products.html — Products listing
- services.html — Services details
- amc.html — AMC plans and benefits
- about.html — Company overview
- contact.html — Contact form and Google Map
- assets/css/styles.css — Main stylesheet (variables, responsive)
- assets/js/main.js — Lightweight interactivity (mobile nav, forms)
- assets/icons.svg — SVG icon sprite

## Quick start
1. Replace placeholder assets:
   - `assets/images/logo-light.svg`, `logo-dark.svg`, `assets/images/*` — replace with your real images and product photos.
   - Update phone and email values in HTML (tel:, mailto:) and in JSON-LD. Current template uses:
     - Phone: +91 8887961171
     - Email: uttam222141@gmail.com
   - Update the Google Maps iframe coordinates in `contact.html`.

2. Deploy:
   - Static hosting recommended: GitHub Pages, Netlify, Vercel, Firebase Hosting, or your own web server.
   - For Netlify/Vercel: push to a GitHub repo and connect the site.
   - Ensure HTTPS for WhatsApp links and SEO.

3. Integrations:
   - Replace contact form behavior with your backend or a serverless form handler (Formspree, Netlify forms, or your API).
   - Add Google Analytics / GTM (insert `script` tags into head).
   - Add structured data (JSON-LD) details in `index.html` and other pages.

## SEO & Performance Tips
- Use semantic tags and headings for accessibility & SEO.
- Compress images (WebP preferred) and use srcset for responsive images.
- Add critical CSS and defer non-essential CSS for faster render.
- Use server-side caching / CDN for static assets.
- Add sitemap.xml and robots.txt for search engines.
- Provide Open Graph and Twitter Card meta tags on pages to improve link previews.

## Accessibility & UX
- Buttons and links use large tap targets for mobile.
- Form labels and ARIA attributes are included.
- Color contrast selected for readability; test with accessibility tools.

## Customization Checklist
- Replace phone/email and address with your official details (currently set to +91 8887961171 and uttam222141@gmail.com).
- Add real product and case-study images.
- Add customer testimonials and logos (trust badges).
- Create server-side endpoint or service to process contact forms.
- Add privacy policy and terms pages if required.

If you want, I can:
- Connect the contact form to an email / CRM (SendGrid, Mailgun).
- Add a CMS (Headless / Netlify CMS) to manage products & services.
- Create a ready-to-deploy GitHub repo and CI configuration for automatic deployment.