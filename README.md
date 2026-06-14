# License Renewal Landing Page

A responsive landing page built as a frontend practice project using HTML, CSS, JavaScript, and React (via CDN). The project focuses on semantic structure, responsive layouts, accessibility considerations, interactive UI components, and modern CSS techniques without relying on external UI frameworks.

## Overview

This project simulates a software license renewal and support services website. It includes a responsive navigation system, marketing sections, pricing/support comparison tables, FAQ accordions, contact links, and a multi-column footer.

The goal was to practice building a complete landing page while exploring advanced CSS layout techniques, accessibility features, state-driven UI behavior, and component-based rendering.

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* React 18 (CDN)
* ReactDOM 18 (CDN)
* Babel Standalone

No CSS frameworks or component libraries were used.

---

## Features

### Responsive Navigation

* Navigation rendered using a React component.
* Mobile navigation controlled through React state.
* Custom hamburger menu built entirely with CSS.
* Animated slide-down menu for smaller screens.
* Keyboard-accessible menu interactions.
* SVG-based navigation icons.

### Responsive Layout

* Mobile-first design approach.
* Layout adjustments using media queries.
* Flexbox-based section layouts.
* Grid-based comparison table on larger screens.
* Optimized layouts for screens above and below 600px.

### Modern CSS Techniques

* Flexbox layouts.
* CSS Grid layouts.
* Container queries and container units.
* CSS custom properties (variables).
* Aspect-ratio based sizing.
* Clamp-based responsive typography and spacing.
* Pseudo-elements for decorative and functional effects.
* Custom transitions and animations.

### FAQ Accordion System

* Expand/collapse FAQ entries.
* Smooth height-based transitions.
* Dynamic animation duration calculated from content height.
* Keyboard support for accessibility.
* Custom toggle controls instead of relying solely on default `<details>` behavior.

### Comparison Table

* Responsive support plan comparison section.
* Mobile-friendly stacked layout.
* Desktop grid layout using CSS Grid and subgrid techniques.
* Shared layout structure between header and content rows.

### Accessibility Considerations

* Keyboard navigation support.
* Focus-visible states.
* Enter and Space key activation for interactive elements.
* Semantic HTML elements such as:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<footer>`
  * `<details>`
  * `<summary>`

### Contact Options

* Email link
* SMS link
* Telephone link
* WhatsApp link
* Smooth scrolling navigation to contact areas

### Footer

* Multi-column responsive footer.
* Newsletter signup form.
* Structured navigation links.
* Company and support information sections.

---

## React Usage

React is used specifically for the navigation system.

Features include:

* Component-based rendering.
* State management with `useState`.
* Conditional class toggling.
* Dynamic generation of navigation items.
* Keyboard-accessible menu interactions.

---

## Notable Learning Areas

This project was used to practice:

* Building responsive layouts without frameworks.
* Combining Flexbox and CSS Grid effectively.
* Creating custom UI interactions with vanilla JavaScript.
* Working with React state in a mixed HTML/CSS/JS environment.
* Accessibility-focused interaction patterns.
* Advanced CSS sizing and layout techniques.
* Handling browser-specific CSS behavior and layout edge cases.

---

## Project Structure

```text
index.html
│
├── HTML structure
├── CSS styling
├── Vanilla JavaScript interactions
└── React navigation component
```

All code is contained within a single file for learning and experimentation purposes.

---

## Future Improvements

Possible future additions include:

* Full React application structure.
* React Router integration.
* Form validation and backend integration.
* Dark mode support.
* Improved navigation animations.
* CMS or API-driven content.
* Automated testing.
* Performance optimization and asset bundling.

---

## Purpose

This project was created as a frontend development practice exercise to strengthen skills in:

* HTML semantics
* CSS layouts
* Responsive design
* JavaScript DOM manipulation
* React fundamentals
* Accessibility
* UI implementation without external frameworks

It is intended as a learning project and portfolio demonstration rather than a production-ready commercial website.
