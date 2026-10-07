# Brew Haven

Brew Haven is a responsive, single-page coffee shop website built with plain HTML, CSS, and JavaScript. It includes a coffee menu, product gallery, opening hours, contact information, and a contact form.

## Getting started

No build tools or package installation are required.

1. Download or clone this project.
2. Open `index.html` in a web browser.

For a local development server, you can use the **Live Server** extension in Visual Studio Code and choose **Open with Live Server** on `index.html`.

Font Awesome icons are loaded from a CDN, so an internet connection is needed for those icons to appear. The rest of the site is served from the project files.

## Project structure

```text
.
├── index.html       # Page content and structure
├── style.css        # Theme, layout, and responsive styles
├── script.js        # Mobile navigation and header behavior
└── img/
    ├── favicon.svg  # Browser tab icon
    └── ...          # Coffee and product images
```

## Features

- Responsive layout for desktop, tablet, and mobile screens
- Navigation links to the page sections, with a mobile menu
- Coffee menu with prices
- Product image gallery
- Opening hours and contact information
- Contact form with required-field and email-format validation from the browser
- Brew Haven logo and matching SVG favicon

## Updating the site

- Edit the text and page sections in `index.html`.
- Adjust colors, spacing, components, and breakpoints in `style.css`.
- Update navigation behavior in `script.js`.
- Replace or add images in `img/`, then update the corresponding image paths in `index.html` or `style.css`.

The contact form currently provides browser-side validation only. Connecting it to a form service or backend is required to receive submissions.
