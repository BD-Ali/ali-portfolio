# Portfolio

This repository contains my personal portfolio website built directly from the information in my résumé. The design embraces a **creative dark theme** with smooth scroll animations and interactive elements. Sections fade into view as you scroll down the page, leveraging the Intersection Observer API to trigger CSS transitions when content enters the viewport【89040023436198†L316-L334】.

## Features

- **Animated sections:** Each section of the page slides and fades into place as you scroll, providing a polished and dynamic feel. The Intersection Observer API monitors when elements enter the viewport and adds classes to trigger animations【89040023436198†L316-L334】.
- **Dark theme aesthetic:** A sophisticated palette of deep blues and purples with bright accent colours creates a modern and professional look.
- **Icon‑based contact links:** Prominent links to my GitHub profile, LinkedIn (placeholder) and downloadable résumé appear alongside the hero section, using Font Awesome icons for clarity.
- **Responsive design:** The layout adapts to different screen sizes, ensuring a consistent experience on desktop and mobile devices.

## Contents

- **index.html** – The main web page that implements the animated, dark‑themed portfolio. It includes sections for About, Education, Skills, Project, Experience and Interests.
- **Ali_Badarne_Resume.pdf** – My résumé, available for download directly from the site.

## Build Details

The site uses plain HTML, CSS and a small amount of JavaScript to implement the scroll animations. The Intersection Observer pattern is based on a technique where a callback function adds an `inview`/`show` class when an element becomes visible in the viewport【89040023436198†L316-L334】. This class triggers CSS transitions for opacity and translation, creating a smooth fade‑in effect.

To view the portfolio locally, simply open `index.html` in a web browser. The site is static and does not require any build tools or frameworks.

---

Download my résumé here: **[Ali_Badarne_Resume.pdf](./Ali_Badarne_Resume.pdf)**