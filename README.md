# Bento Showcase Layout

A clean, responsive CSS Grid bento layout engineered for modern product landing pages, dashboards, and feature highlights. Built with vanilla HTML5 and custom CSS custom properties, it delivers a sleek dark-mode design system with zero external build dependencies.

## Overview

Most landing page grids crumble when forced into responsive viewports or require heavy framework dependencies like Tailwind or Bootstrap just to display structured feature cards. 

This repository provides an idiomatic CSS Grid layout utilizing explicit column spans, CSS variables, and dynamic breakpoint handling. It handles grid re-layouts across large, medium, and mobile viewports cleanly.

## Key Features

* **CSS Grid Bento Architecture**: Uses `repeat()`, `minmax()`, and grid-column/row spanning to structure visual hierarchy naturally.
* **Responsive Breakpoint Cascade**: Desktop 4-column layout gracefully falls back to a 2-column view on tablets and a single-column stack on mobile viewports.
* **Dark Theme Design System**: Built with modern slate CSS variables (`--bg-color`, `--card-bg`, `--accent-grad`) for consistent branding and contrast[cite: 1].
* **Zero Dependencies**: Pure HTML5 and CSS3—no npm packages, build steps, or external assets required.

## Tech Stack Breakdown

* **HTML5**: Semantic document structure using `<main>`, `<header>`, and standalone feature cards[cite: 2].
* **CSS3**: Custom Properties (variables), Flexbox layout alignment within cards, CSS Grid layout math, and media query breakpoints[cite: 1].

## Prerequisites & Web-Based Quick Start

Since this is a lightweight static layout, you can preview and edit it directly in your browser without installing anything locally.

### Option A: GitHub Codespaces (Browser Only)
1. Click the **Code** button at the top right of this repository.
2. Select the **Codespaces** tab and click **Create codespace on main**.
3. Once the environment opens, use the **Live Server** extension or open `index.html` directly in your browser[cite: 2].

### Option B: Local Browser Preview
1. Clone or download the repository.
2. Double-click `index.html` to open it in any modern browser[cite: 2].

## Project Structure

```text
├── index.html        # Main HTML layout featuring the bento grid markup
└── style.css         # CSS Grid styles, custom properties, and responsive queries
```

## Roadmap

- [ ] Add interactive hover animations with CSS transitions.
- [ ] Add an optional light mode toggle via CSS variable swapping.
- [ ] Create a Tailwind CSS variant for project parity.
