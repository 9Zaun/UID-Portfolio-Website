# Portfolio Website

Here's a portfolio website I built using HTML, CSS and some JavaScript.
It's inspired by Apple's product webpages and focuses on minimalistic design, clarity, contrast and interaction.
The design is meant to look clean and consistent across all webpages.

---

## Structure

The website comprises of 4 pages:
- `index.html` : is the homepage/landing page that includes an About Me section
- `projects.html` : is an interactive project showcase (potential future projects) using a quadrant layout
- `skills.html` : uses cards in a grid to display skillset
- `contact.html` : utilises a form for simple contact functionality

Additionally, all pages share the stylesheet:
- `styles.css`

---

## Design System

- Color Scheme: Strictly black and white, with the exception of bold, high resolution, clean images (no backgrounds)
- Font: Inter font (font similar to Apple's)
- Layout: uses containers, content is centered
- Sections: alternating black and white backgrounds, with white and black borders/text respectively
- Spacing: I wanted the landing page to be ultra clean and take the whole height of the screen, giving extra details only upon scrolling- thus spacing was modified to accommodate that

---

## Key Features

### Interactive Quadrant for Projects Page
Used a 2x2 quadrant grid, each quadrant expands on hover and maximises on click (only up to the nav bar)
This expansion uses JavaScript
CSS handles transitions using `transform`, `opacity`

#### Minimal JavaScript
Toggled an `active` class to trigger css animations


### Skills Grid
Used a card based layout that inverts its colour scheme on hovering with mouse. 
Adds to the contrast and boldness.

### Responsive Design
For mobiles, there's a breakpoint that collapses grid layouts into a single column, and images/sections are adapted accordingly.

---


Created by: Jayanth Jayaprakash, S2 CSE A 2025-2029, am.sc.u4cse25038


