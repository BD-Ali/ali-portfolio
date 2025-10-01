# Portfolio

This repository hosts my personal portfolio website, built from the key information in my résumé. The site uses a sophisticated dark theme and interactive animations to present my background as a software engineering student and backend developer. Each section elegantly slides into view as you scroll, and the navigation bar highlights the active section, making it easy to follow along.

## Key Features

- **Dark, animated design:** The hero section features a subtle, animated gradient backdrop that cycles across deep blues and purples, providing a modern foundation for the content.
- **Scroll‑aware navigation:** Links in the navigation bar highlight automatically based on your position on the page, giving clear context as you explore.
- **Slide‑in animations:** Content cards for each section (About, Education, Technical Skills, Project, Experience and Interests) slide from alternating directions and fade in smoothly. These effects are powered by the Intersection Observer API, which adds a class when elements enter the viewport【89040023436198†L316-L334】.
- **Progress indicator & back‑to‑top button:** A thin bar at the top tracks scroll progress, while a floating button appears after you scroll down, allowing you to return smoothly to the top.
- **Interactive cards:** Each information card responds to hover with gentle elevation and shadow changes, adding depth to the design.
- **Prominent contact links:** Icons for my GitHub, LinkedIn (at www.linkedin.com/in/bdali) and résumé download appear in the hero section, ensuring easy access to my profiles.
- **Fully responsive:** The layout adapts gracefully to different devices and screen sizes without additional frameworks.

## Structure

The site is contained in a single `index.html` file and uses plain HTML, CSS and minimal JavaScript. It highlights the following:

- **About Me:** A brief summary of my motivations and technical focus, distilled from my résumé.
- **Education:** B.Sc. in Software Engineering at Azrieli College of Engineering with key courses listed.
- **Technical Skills:** Categorised lists of programming languages, web technologies and tools I use.
- **Featured Project:** Details of a Spring Boot product management system that showcases my backend development skills.
- **Additional Experience:** Summaries of system/network administration and hardware repair experience.
- **Interests:** A snapshot of my hobbies, including chess, volunteer work, car remodeling and cooking.

The site uses the Intersection Observer pattern where a callback function adds a class to each section as it becomes visible in the viewport【89040023436198†L316-L334】. This class triggers CSS transitions for opacity and translation, resulting in the smooth slide and fade animations that give the portfolio its polished feel.

