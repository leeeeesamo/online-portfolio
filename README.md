# **Online Portfolio** 🎨

This repository contains the source code for my personal online portfolio, built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). It is based on the Type-on-Strap theme and customized to showcase projects, posts, and personal content.

---
## **Features**
- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile).
- **Dark Mode Support**: Includes an auto-switch and manual toggle.
- **SEO Optimized**: Pre-configured with Jekyll SEO tag and sitemap generation.
- **Google Analytics**: Integrated for visitor tracking and performance insights.
- **Portfolio Section**: Displays projects and work samples in a dynamic grid layout.
- **Blog Support**: Write posts with tags and excerpts for easy navigation.
- **Math and Diagrams**: Supports rendering with KaTeX and Mermaid.js.
- **Customizable Layouts**: Easily adjustable header, footer, and theme settings.

---
## **Getting Started**

### **1. Installation**
To run this site locally, you’ll need:
- Ruby (2.7 or higher)
- Bundler
- Git

Clone the repository:
	git clone https://github.com/leeeeesamo/online-portfolio.git
	cd online-portfolio

Install dependencies:
	bundle install

### **2. Run Locally**
Serve the site locally:
	bundle exec jekyll serve

Access the site at: http://127.0.0.1:4000

### **3. Build for Deployment**
Build the site for production:
	bundle exec jekyll build

The generated static files will be available in the _site directory.

## **Repository Structure**
```shell
online-portfolio/
├── _includes               # Reusable HTML partials
├── _layouts                # Jekyll layouts (e.g., default, post)
├── _posts                  # Markdown files for blog posts
├── _portfolio              # Markdown files for portfolio items
├── assets
│   ├── css                 # Stylesheets
│   ├── js                  # JavaScript files
│   └── img                 # Images used across the site
├── _config.yml             # Main configuration file
├── Gemfile                 # Ruby dependencies
└── index.html              # Homepage
```

## **Customization**
### **Site Configuration**
Edit _config.yml to update:
- Site title, description, and URL
- Google Analytics ID
- Theme settings (light/dark mode, SEO options)

Example:
title: "Online Portfolio"
description: "A showcase of my work, blog posts, and projects."
google_analytics: G-XXXXXXXXXX
color_theme: auto

---
### **Adding Content**
- Blog Posts: Add .md files to the _posts directory. Use the post layout.
- Portfolio Items: Add .md files to the _portfolio directory. Use the post layout and specify an image.

Example front matter for a portfolio item:
---
layout: post
title: "Project Title"
img: "assets/img/portfolio/project-image.png"
feature-img: "assets/img/portfolio/featured-project.png"
tags: [portfolio, featured]

---
## **Deployment**
This site is hosted via GitHub Pages. To update the live site:

Commit your changes:
	git add .
	git commit -m "Update site content"

Push to the main branch:
	git push origin main

Ensure GitHub Pages is enabled in the repository settings.

---
## **Contributing**
Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions and improvements.

---
## **License**
This project is licensed under the MIT License.

---
## **Acknowledgments**
Built with Jekyll
Inspired by the Type-on-Strap theme
Hosted on GitHub Pages