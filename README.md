# Assignment-1-Cycoders
# Shubham Sinha - Personal Profile Website

## Overview
This is a responsive single-page personal profile website created as an introductory web development assignment. It is built strictly using **pure HTML5 and CSS3** without any JavaScript, external UI frameworks, or CDN libraries.

## Features
- **Pure CSS Dark & Light Mode**: Seamless theme switching with an interactive sun ☀️ / moon 🌙 toggle switch in the navigation bar using CSS variables and `:has()` selectors (0 lines of JavaScript).
- **Semantic HTML5 Structure**: Built using semantic elements (`<header>`, `<main>`, `<section>`, `<footer>`, `<article>`) with a strict heading hierarchy (`h1` for name, `h2` for section titles, `h3` for cards).
- **Modern CSS Styling**: Custom styling in an external stylesheet (`css/style.css`) using CSS Custom Properties (variables), Flexbox, and CSS Grid.
- **Card-Based UI**: Box / card styling with rounded corners, subtle shadows, tag badges, and smooth hover elevation effects for skills, projects, and contact cards.
- **Accessible Navigation**: Sticky header with anchor links (`#about`, `#skills`, `#projects`, `#contact`) and smooth scrolling.
- **Fully Responsive**: Optimized for mobile screens (~375px) as well as tablet and desktop viewports using media queries.
- **Interactive Links**: Direct `mailto:` email link and clear placeholder links for GitHub and LinkedIn profiles.

## File Structure
```text
Webpage Assignment 1/
│
├── index.html        # Main HTML document with semantic structure, theme toggle & content
├── css/
│   └── style.css     # External stylesheet with light/dark theme variables & card styling
├── images/
│   ├── profile.jpg   # Profile picture file
│   └── code-icon.png # Favicon icon
└── README.md         # Documentation & instructions
```

## How to Open and View

### Option 1: Direct File Opening
1. Navigate to the folder in your file explorer.
2. Double-click on `index.html` (or right-click `index.html` > **Open with** > your preferred browser).

### Option 2: Live Server in VS Code
1. Open the project folder in **Visual Studio Code**.
2. If you have the **Live Server** extension installed, right-click `index.html` and select **Open with Live Server**.
3. The page will open automatically in your browser at `http://127.0.0.1:5500/index.html`.

## Customization
- **Profile Image**: Replace `images/profile.jpg` with your own photo (square 400x400 px recommended).
- **Social Links**: Replace placeholder URLs (`github.com/yourusername`, `linkedin.com/in/yourusername`, and `leetcode.com/yourusername`) in `index.html` with your real profile links.
