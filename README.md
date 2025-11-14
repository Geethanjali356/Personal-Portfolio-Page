# Responsive Personal Portfolio

This repository contains a fully responsive personal portfolio webpage built using only HTML and CSS.

## 📝 Project Requirements Fulfilled

* **Sections:** Includes Header, Hero, About, Skills, and Footer.
* **Header:** Contains Name/Logo and Navigation links (Home, About, Skills, Contact).
* **Hero Section:** Includes a headline, description, and "Contact Me" button.
* **Skills Section:** Features a grid layout with 6 skills.
* **Footer:** Contains social media links.
* **Responsiveness:** Fully responsive for Desktop, Tablet, and Mobile views.
    * **Desktop (≥1024px):** Navigation links in a row.
    * **Tablet (768–1023px):** Skills grid is 2-column.
    * **Mobile (≤767px):** Hamburger menu for navigation, Skills grid is 1-column, no horizontal scroll.

## 🤖 AI Tool Usage

This project was initiated using **Generative AI (Large Language Model)** to rapidly create the structural and stylistic foundation.

* **AI Tool Used:** Large Language Model (LLM) / Generative AI
* **Generated Part:** The complete initial `index.html` structure and the base `style.css` file, including all sections, initial layout, and media query definitions.

## ✍️ Manual Edits and Customization

The AI-generated code was reviewed, fixed, and enhanced manually to ensure compliance with all requirements and to add bonus features.

* **Accessibility & Structure:**
    * Added `aria-label` to the hamburger icon and social links.
    * Ensured semantic HTML elements (`<header>`, `<main>`, `<section>`, `<footer>`).
    * Fixed the Mobile Navigation menu logic with a simple JavaScript toggle, ensuring it closes when a link is clicked.
* **Design & Styling (Bonus Features):**
    * **Unique Color Theme:** Defined CSS variables (`:root`) for easy theme customization (currently a modern Blue theme).
    * **Subtle Animation (CSS Only):** Added a `fadeIn` keyframe animation for the Hero section content and a staggered animation for the Skills cards.
    * **Simple Card Hover Effect:** Applied a subtle `transform: translateY(-5px)` on hover to the skill cards for an interactive feel.
* **Responsiveness Fine-Tuning:**
    * Explicitly set `overflow-x: hidden;` on `html` and `body` to strictly prevent horizontal scrolling on mobile.
    * Adjusted the `skills-grid` media queries to correctly transition from 3-column (desktop) to 2-column (tablet) to 1-column (mobile).
    * Implemented the Hamburger menu transition using CSS `transform` properties.
