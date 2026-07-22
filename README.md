# Bento Showcase Layout

A clean, responsive UI layout pattern built with modern CSS Grid and custom variables. Designed specifically for SaaS product landing pages that need to showcase features in an engaging, asymmetric "bento box" arrangement.

---

## Overview

Most landing page feature sections rely on repetitive, boring three-column card grids. This project provides a flexible, dependency-free CSS Grid framework that handles complex card spanning (`large`, `tall`, `medium`, `small`) while remaining responsive down to mobile viewports.

It uses zero framework overhead—just semantic HTML5 and vanilla CSS utilizing modern layout primitives.

---

## Key Features

* **Asymmetric Grid Architecture:** Built on a 4-column dynamic CSS Grid setup that handles multi-row and multi-column spans smoothly.
* **Fluid Responsive Design:** Automatically reflows from a 4-column desktop layout to a 2-column tablet layout, and collapses down to a single column on mobile devices.
* **CSS Custom Properties:** Centralized color palettes and styling rules defined at the root level for easy theme swapping (dark mode ready).
* **Zero Dependencies:** No Bootstrap, Tailwind, or JavaScript runtime needed. Instant load times and zero build steps.

---

## Tech Stack Breakdown

* **HTML5:** Semantic document structure using `<main>`, `<header>`, and inline SVG/emoji primitives.
* **CSS3:** Native CSS Grid (`repeat()`, `minmax()`, `grid-column`, `grid-row`), Flexbox for card content alignment, and CSS Variables (`:root`).

---

## Prerequisites & Web-Based Quick Start

You don't need to clone this locally or open a terminal. You can run and inspect this project entirely inside your browser.

### Option A: Using GitHub Codespaces
1. Click the **Code** button at the top right of this repository.
2. Select the **Codespaces** tab and click **Create codespace on main**.
3. Once the environment loads, install the **Live Preview** extension in VS Code.
4. Right-click `index.html` and select **Live Preview: Show Preview**.

### Option B: Quick Local View
1. Download the ZIP file of this repo.
2. Extract it and double-click `index.html` to open it in any web browser.

---

## Project Structure

```text
bento-grid-showcase/
├── index.html        # Semantic HTML layout structure
└── style.css         # CSS Grid definitions and custom variables
```

## Roadmap
[ ] Add built-in light/dark theme toggle snippet.

[ ] Include subtle entry animations for cards using native @keyframe animations.

[ ] Expand template variations for developer portfolio sections.
