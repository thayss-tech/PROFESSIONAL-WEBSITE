<div align="center">
  <h1>Thayss Tech Hub</h1>
  <p><strong>Applied Data Science Portfolio</strong></p>

  <p>
    <a href="https://thayss-tech.github.io/WEB/">
      <img src="https://img.shields.io/badge/Website-Live-2ea44f?style=for-the-badge" />
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    </a>
  </p>
</div>

---

## 📑 Table of Contents

- [Overview](#overview)
- [Architectural Model](#architectural-model)
- [Core Engine: assets/](#core-engine-assets)
- [Single Page Structure](#single-page-structure)
- [Visual & Media Layer](#visual--media-layer)
- [Professional Validation](#professional-validation)
- [Repository Map](#repository-map)
- [Deployment](#deployment)
- [Contact](#contact)

---

# Overview

This repository contains the full source code of my professional website.

It functions as a **centralized technical hub**, designed to:

- Present my background in Theoretical Physics  
- Showcase applied Data Science projects  
- Connect Machine Learning systems  
- Provide structured access for technical evaluation  

The objective is clarity, structure and technical transparency.

---

# Architectural Model

The website follows a **Single Page Architecture (SPA-style static model)**.

```
User → index.html → assets/ (logic + style) → media → certificates
```

There are no heavy frameworks or unnecessary dependencies.  
The structure prioritizes:

- Performance  
- Readability  
- Maintainability  
- Full control over the frontend stack  

---

# Core Engine: assets/

The `assets/` directory is the operational core of the platform.

## 1️⃣ assets/css/ — Visual System

Controls the entire visual identity:

- Layout structure  
- Color palette  
- Typography  
- Responsive behavior  
- Component styling  

Key files:

- **main.css** → Main visual system  
- **fontawesome-all.min.css** → Icon rendering engine  
- **noscript.css** → Fallback design if JavaScript is disabled  

---

## 2️⃣ assets/js/ — Interaction Layer

Adds dynamic behavior and responsiveness.

Key scripts:

- **main.js** → Smooth scrolling, animations, interaction logic  
- **jquery.min.js** → JavaScript utility library  
- **browser.min.js** → Browser detection and compatibility  
- **breakpoints.min.js** → Responsive behavior controller  
- **util.js** → Supporting helper functions  

Without this layer, the site would be static.

---

## 3️⃣ assets/sass/ — Design Engineering Layer

Professional CSS architecture built using SASS.

This allows:

- Variable management (colors, spacing, typography)  
- Modular component design  
- Maintainable and scalable styling  

Important structure:

- `main.scss` → Main source styling  
- `_vars.scss` → Design constants  
- `_mixins.scss` → Reusable styling logic  
- `components/` → Buttons, forms, menus  
- `layout/` → Structural layout rules  

These files compile into the final `main.css`.

---

## 4️⃣ assets/webfonts/ — Icon Infrastructure

Contains the FontAwesome font files:

- fa-brands  
- fa-regular  
- fa-solid  

Multiple extensions (.woff, .woff2, .ttf, .eot, .svg) ensure cross-browser compatibility across:

- Chrome  
- Safari  
- Firefox  
- Edge  
- Legacy systems  

---

# Single Page Structure

## index.html — Structural Core

This is the master document containing:

- Name & professional summary  
- Project sections  
- Contact links  
- Navigation structure  

The site scrolls vertically in structured content blocks.

---

# Visual & Media Layer

## images/

Contains visual assets:

- Tool icons (n8n, workflow systems)  
- Profile and presentation images  
- Device visuals  
- Technical stack representation  

These elements reinforce professional identity.

---

# Professional Validation

## certificates/

Documents that validate technical expertise:

- GCP Certification  
- Machine Learning with Python  
- Additional credentials  

These act as credibility anchors.

---

# Repository Map

```
WEB/
 ┣ index.html
 ┣ assets/
 ┃ ┣ css/
 ┃ ┣ js/
 ┃ ┣ sass/
 ┃ ┗ webfonts/
 ┣ images/
 ┣ certificates/
 ┣ LICENSE
 ┗ README.md
```

### Structural Separation

- Structure → HTML  
- Style → CSS / SASS  
- Logic → JavaScript  
- Media → images/  
- Validation → certificates/  

---

# Deployment

Hosted via GitHub Pages.

Live version:  
https://thayss-tech.github.io/WEB/

The deployment model ensures:

- Static reliability  
- Fast loading  
- No backend dependency  

---

# Contact

GitHub: https://github.com/thayss-tech  
LinkedIn: www.linkedin.com/in/milton-mamani-1369a537b  

---

⭐ Designed as a structured technical gateway for data-driven environments.
