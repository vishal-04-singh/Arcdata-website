# ArcData Technology Website

Welcome to the **ArcData Technology** official front-end repository. ArcData is a premier data services provider specializing in high-quality data collection, annotation, and processing to fuel the most innovative Artificial Intelligence (AI) systems globally.

## 🌐 Overview

This repository contains the complete front-end source code for the ArcData Technology corporate website. The website is designed to showcase our diverse AI data services, industries served, company mission, and strict adherence to global data security standards.

The UI is built with a strong focus on responsiveness, interactivity, and modern web design principles, featuring custom animations, interactive tabs, and device-specific layouts.

## ✨ Key Features

* **Custom Interactive UI:** Homepage features an animated hero carousel, interactive service tabs, and animated statistics counters.
* **Fully Responsive Design:** Employs a unique device-specific CSS architecture targeting iPhone (portrait/landscape), iPad (portrait/landscape), and Desktop environments for pixel-perfect rendering.
* **Scroll Animations:** Elements fade in and slide up as they enter the viewport to create an engaging browsing experience.
* **Modular Codebase:** Each core page (Home, Services, Industries, Company, Contact) has its dedicated HTML, CSS, and JavaScript file, ensuring clean separation of concerns.
* **SCSS Preprocessing:** Uses SCSS (`style2.scss`) for maintainable and scalable styling.

## 🚀 Services Showcase

The website details ArcData's core offerings:

* **Data Annotation:** High-quality labeling for Image, Video, Audio, and Text. Includes 2D/3D bounding boxes, polygons, landmarks, key-points, and semantic segmentation.
* **Data Collection:** Gathering diverse datasets, including facial imagery, video, audio transcripts, and comprehensive text data.
* **OCR Data:** Optical Character Recognition data services.
* **NLP:** Natural Language Processing and Speech-to-Text data solutions.

## 🏢 Industries Served

Tailored data solutions for various sectors highlighted in the `industries.html` page:

* Healthcare & Agriculture
* Manufacturing & Technology
* Gaming & Sports
* Education & Government

## 🛡️ Compliances & Security

We proudly display our commitment to data security and client trust:

* **ISO 27001** & **ISO 9001** Certified
* **GDPR** & **HIPAA** Compliant
* Robust encryption for data in transit and at rest to mitigate breach risks.

## 🛠️ Tech Stack & Architecture

* **HTML5:** Semantic architecture with optimized sections for scroll-triggered reveal animations.
* **CSS3 & SCSS:**
  * `style.css`: Main desktop styling.
  * `style2.scss` / `style2.css`: Preprocessed styles utilizing SCSS extensions.
  * `[device]-[orientation].css`: Breakpoint-specific stylesheets (e.g., `ipad-landscape.css`, `iphone-portrait.css`).
  * Page-specific styles (e.g., `company-style.css`, `services-style.css`, `industry-style.css`).
* **JavaScript (Vanilla):**
  * `file.js`, `company-file.js`, `industry-file.js`, `services-file.js`: Handle sliders, hamburger menus, number counters, and tab switching logic.
* **Assets:** FontAwesome icons, inline SVG graphics, and optimized mp4 background videos.

## 📁 Repository Structure

```text
arcData/
├── index.html                  # Main Landing Page
├── services.html               # Services Overview Page
├── industries.html             # Industries Served Page
├── company.html                # About Us & Case Studies
├── touch.html                  # Contact & Inquiry Page
├── assests/                    # Images, Videos, PDFs, SVGs, Fonts
├── *.js                        # Page-specific JavaScript logic files
├── *.css                       # Main, Page-specific, and Responsive Stylesheets
├── style2.scss                 # SCSS source file
└── style2.css.map              # SCSS source map
```

## 💻 Getting Started (Local Development)

To view and modify this project locally:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd arcData
   ```
2. **Open the application:**
   Simply open `index.html` in your preferred modern web browser. No local development server is strictly needed, but using one (like VS Code Live Server) is heavily recommended to avoid CORS issues with local assets.

   ```bash
   open index.html # macOS
   start index.html # Windows
   ```
3. **SCSS Compilation (Optional):**
   If you wish to edit `style2.scss`, you will need a SASS compiler to watch for changes and compile them to `style2.css`.

   ```bash
   # If you have sass installed globally:
   sass --watch style2.scss style2.css
   ```

## 📞 Contact & Links

* **Website:** [arc-data.in](https://arc-data.in)

---

*Copyright © 2023. Designed by Team ArcData.*
