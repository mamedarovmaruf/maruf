# Maruf's Tech & AI Blog

A lightweight personal blog website focused on technology, artificial intelligence, and modern digital culture. The project is a static, single-page blog built with plain HTML, CSS, and JavaScript, designed to be fast, responsive, and easy to maintain.

Live site: https://maruf.moolvylabs.org/

## Overview

This repository hosts the source code for my personal blog. It includes:

- bilingual content in English and Russian
- light and dark theme switching
- built-in search across posts
- responsive layout for desktop and mobile
- custom domain support via a static hosting setup
- zero-framework architecture for simplicity and performance

## Features

- Minimal static site structure
- Fast loading and easy deployment
- Clean editorial presentation for blog posts
- Search by post number or keyword
- Theme toggle for reading comfort
- Author branding and custom favicon

## Project structure

```text
.
├── CNAME
├── favicon.png
├── index.html
├── LICENSE
├── README.md
├── post1.jpg
├── post2.jpg
├── post3.png
├── post4.png
├── post5.png
├── post6.jpg
├── post6.png
├── post7.jpg
├── post8.jpg
└── ...
```

## Local development

Because this is a static site, you can preview it locally without installing a framework.

### Option 1: open directly

Open `index.html` in your browser.

### Option 2: run a local web server

From the project root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

This site is designed for simple static hosting. If you deploy to GitHub Pages, Netlify, Vercel, or any static web host, the project should work as-is.

If using a custom domain, the `CNAME` file is already included for domain configuration.

## Notes

- The site content is embedded directly in `index.html`.
- Styling and interaction logic are included in the same file for a compact and easy-to-edit setup.
- Images and blog posts can be added or updated by editing the `blogData` array in the JavaScript section.

## License

This project is distributed under the repository license. Please see the `LICENSE` file for full details.

## Author

Maruf Mamedarov

Website: https://maruf.moolvylabs.org/
