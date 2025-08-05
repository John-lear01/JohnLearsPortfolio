# John Lear Portfolio

This repository contains the source files for **John Lear's engineering portfolio** website hosted on GitHub Pages.  The site is a single‑page application built with plain HTML and [Tailwind CSS](https://tailwindcss.com/) that showcases John's education, featured projects, professional experience, and contact information.

## Structure

- **index.html** – the main landing page for the portfolio.  It includes a hero section, about and education sections, a featured projects grid, professional experience, and a “Get in Touch” contact form.
- **portfolio.html** – an alternate entry point containing the same content as `index.html` but separated for convenience.
- **vertical-axis-wind-turbine.html**, **altitude-chamber.html**, **heating-load-calculation.html** – dedicated pages for each featured project.  Each page describes the project, lists highlights, provides supporting documents, and contains an image gallery.
- **images/** – contains all of the photographs and rendered images used throughout the site.  Keeping images in their own folder helps keep the repository tidy and makes it easy to update paths in the HTML.
- Additional PDF and spreadsheet files in the root directory are linked from the project pages as supporting documents.

## Contact Form

The “Get in Touch” form on the site uses [Formspree](https://formspree.io/) to handle submissions.  A small JavaScript snippet intercepts the form’s submit event, packages the form data as JSON, and sends it to Formspree’s endpoint.  Upon successful submission, the user sees a thank‑you message and the form resets.

## Development

To run the site locally, clone the repository and open `index.html` in your browser.  Because the site is entirely static, no build process is required.  The styling is powered by Tailwind CSS via its CDN.  Feel free to fork the repository and customize it for your own portfolio.

## Deployment

This site is deployed via **GitHub Pages**.  Whenever changes are committed to the `main` branch, GitHub automatically rebuilds and publishes the site.  You can view the live portfolio at:

<https://john-lear01.github.io/JohnLearsPortfolio/>
