# Leandro Locsin Exhibit

## Overview

**Leandro V. Locsin** is a multi-page static virtual exhibition website designed to celebrate and explore the life, architectural philosophy, curated portfolio, and national legacy of **National Artist for Architecture Leandro V. Locsin**. Built as a comprehensive digital retrospective, the site features dedicated interactive pages examining his biographical timeline, core design framework (tropical modernism, floating volumes, and chiaroscuro), architectural masterpieces, heritage conservation debates, and academic citations.

## Context

This project was created as the **Midterm Project for Art Appreciation** at [De La Salle University - Dasmariñas](https://www.dlsud.edu.ph/).

To fulfill project guidelines, the website serves as a professional virtual exhibition dedicated to an assigned artist from the Order of National Artists. It assesses the team's mastery of digital curation, appreciation of local arts, and collaborative application of 21st-century skills by demonstrating:

- **Conceptualization & Investigation:** Collaborative artist selection and historical contextualization of National Artist Leandro V. Locsin.
- **Curation & Analysis:** Selection of five (5) architectural works reflecting stylistic evolution, with formal informational text analyzing Elements and Principles of Art.
- **Multi-Page Web Execution:** A structured, multi-page static web application integrating semantic markup, custom CSS styling, and responsive user interfaces.

## Live Preview

You can view and interact with the fully deployed version of the website: <br>
**[Leandro Locsin Exhibit Live Site](https://franciskendrick.github.io/leandro-locsin-exhibit/)**

## Requirements & Setup

### Prerequisites

- **Web Browser:** Any modern browser (Google Chrome, Firefox, Safari, Edge)
- **External Packages:** None (pure static HTML/CSS/JS)

### How to Run Locally

1. Clone this repository:

```bash
git clone https://github.com/franciskendrick/leandro-locsin-exhibit.git
cd leandro-locsin-exhibit
```

## File Structure
```bash
Leandro-V-Locsin-Exhibit/
├── index.html           # Homepage / Exhibition Portal
├── biography.html       # Early life, education, career timeline, and accolades
├── philosophy.html      # Architectural philosophy, tropical modernism, and art theory
├── works.html           # Curated exhibition gallery of major architectural works
├── legacy.html          # Lasting national impact, heritage conservation, references, and team credits
├── css/
│   └── style.css
└── assets/              # Archival photos, portraits, building photography, and team headshots
```

## Recomendations
Based on the development experience of building this virtual exhibition, the development team recommends the following improvements for future iterations:

### 1. Cross-Compatibility and Responsive Design
* **Issue:** The current layout fails to adapt dynamically to different screen sizes.
* **Recommendation:** Implement [CSS Media Queries](https://www.w3schools.com/css/css3_mediaqueries.asp) or a responsive layout model (like [Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) or [Grid](https://www.w3schools.com/css/css_grid.asp)) to ensure the website automatically scales and formats correctly across all platforms.

### 2. Page Transitions and Animations
* **Issue:** Navigating between the different car categories and pages feels abrupt and entirely static.
* **Recommendation:** Utilize [CSS transitions](https://www.w3schools.com/css/css3_transitions.asp) and keyframe animations to create smooth hover effects and fluid page routing.

### 3. Standardized Typography & Modular Scale
* **Issue:** Font sizes for subtitles, cards, and metadata were chosen arbitrarily (e.g., mixing 12px and 14px) on the fly without a consistent scale.
* **Recommendation:** Use a modular typographic scale based on Robert Bringhurst's [The Elements of Typographic Style](https://readings.design/PDF/the_elements_of_typographic_style.pdf) and an 8px grid baseline. This ensures all font sizes follow mathematical proportions for a clean visual hierarchy.

### 4. Collaborative UI Component Standards & Team Communication
* **Issue:** Button styles were inconsistent because team members styled them independently (e.g., some button hovers shifted to dark green while others shifted to light green).
* **Recommendation:** Establish a centralized design system at the start of the project and keep team members aligned on button states, colors, and padding to ensure visual cohesion.
