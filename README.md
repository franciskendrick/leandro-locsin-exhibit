# Leandro Locsin Exhibit


## Overview

**Leandro V. Locsin** is a multi-page static virtual exhibition website designed to celebrate and explore the life, architectural philosophy, curated portfolio, and national legacy of **National Artist for Architecture Leandro V. Locsin**. Built as a comprehensive digital retrospective, the site features dedicated interactive pages examining his biographical timeline, core design framework (tropical modernism, floating volumes, and chiaroscuro), architectural masterpieces, heritage conservation debates, and academic citations.

## Context

This project was created as an academic digital curation project at [De La Salle University - Dasmariñas](https://www.dlsud.edu.ph/).

To fulfill project guidelines, the website serves as a professional virtual exhibition dedicated to an assigned artist from the Order of National Artists. It assesses the team's mastery of digital curation, appreciation of local arts, and collaborative application of 21st-century skills by demonstrating:

- **Conceptualization & Investigation:** Collaborative artist selection and historical contextualization of National Artist Leandro V. Locsin.
- **Curation & Analysis:** Selection of high-resolution architectural works reflecting stylistic evolution, paired with formal informational text analyzing Elements and Principles of Art.
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
* **Issue:** While structured cleanly across standard viewports, certain complex grid layouts require tighter adaptation for mobile breakpoints.

* **Recommendation:** Implement robust CSS Media Queries alongside fluid unit scaling (such as clamp()) to ensure seamless responsiveness across mobile phones and tablets.

### 2. Page Transitions and Animations
* **Issue:** Navigation between pages is instantaneous but visually abrupt without transitional cues.

* **Recommendation:** Utilize CSS transitions and lightweight keyframe animations to introduce smooth page fading and refined hover feedback.

### 4. Standardized Typography & Modular Scale

- **Issue:** Font sizes for subtitles, cards, and metadata were chosen arbitrarily (e.g., mixing 12px and 14px) on the fly without a consistent scale.
- **Recommendation:** Use a modular typographic scale based on Robert Bringhurst's [The Elements of Typographic Style](https://readings.design/PDF/the_elements_of_typographic_style.pdf) and an 8px grid baseline. This ensures all font sizes follow mathematical proportions for a clean visual hierarchy.

### 5. Collaborative UI Component Standards & Team Communication

- **Issue:** Button styles were inconsistent because team members styled them independently (e.g., some button hovers shifted to dark green while others shifted to light green).
- **Recommendation:** Establish a centralized design system at the start of the project and keep team members aligned on button states, colors, and padding to ensure visual cohesion.