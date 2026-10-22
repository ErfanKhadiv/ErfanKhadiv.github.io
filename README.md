# Erfan Khadiv, Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Languages](https://img.shields.io/badge/Languages-English%20%7C%20Persian%20(RTL)-blue)
![Theme](https://img.shields.io/badge/Theme-Dark%20%7C%20Light-lightgrey)
![Hosting](https://img.shields.io/badge/Hosting-GitHub%20Pages-brightgreen)

Personal portfolio of Erfan Khadiv, a computer engineering graduate interested in algorithms, software and artificial intelligence. It is a single static page built with plain HTML, CSS and a little JavaScript, with no framework, build step or dependencies to install. The site is available in **English and Persian (right-to-left)** and in **dark and light mode**. At the top of the page, an animated map runs HBALS, my Traveling Salesman Problem algorithm, live in the browser.

**[Visit the site: erfankhadiv.github.io](https://erfankhadiv.github.io/)**

[![Portfolio hero section in dark mode](docs/screenshots/Dark_Mode_En.png)](https://erfankhadiv.github.io/)

## Contents

- [Preview](#preview)
- [Sections](#sections)
- [Features](#features)
- [Concepts and skills covered](#concepts-and-skills-covered)
- [Project structure](#project-structure)
- [Setup and running](#setup-and-running)
- [Deployment](#deployment)
- [Related projects](#related-projects)
- [License](#license)

## Preview

| Dark mode | Light mode |
| --- | --- |
| [![Dark mode](docs/screenshots/Dark_Mode_En.png)](docs/screenshots/Dark_Mode_En.png) | [![Light mode](docs/screenshots/Light_Mode_En.png)](docs/screenshots/Light_Mode_En.png) |

| Persian (RTL) |
| --- |
| [![Persian version](docs/screenshots/Dark_Mode_Fa.png)](docs/screenshots/Dark_Mode_Fa.png) |

## Sections

| Section | What it contains |
| --- | --- |
| Hero | Name, a short tagline and the live HBALS map |
| Research | The HBALS project: what it solves and how it performed |
| About | A short introduction and areas of interest |
| Projects | Selected work with demos and code |
| Skills | Languages, tools and topics |
| Education | Degree, IELTS and certificates |
| Experience | An internship story |
| Contact | Ways to get in touch |

## Features

- Dark mode by default, with a light mode toggle that is remembered between visits
- English / Persian switch with a full right-to-left layout
- Frosted-glass menu that highlights the section you are viewing
- Back-to-top button
- Live, interactive HBALS demo running on real TSPLIB benchmark instances
- Responsive layout and keyboard-friendly controls

## Concepts and skills covered

- **Front-end fundamentals:** semantic HTML, CSS theming, vanilla JavaScript, no build tooling
- **Internationalization:** bilingual content with a full right-to-left layout for Persian
- **Interaction design:** dark and light themes, scroll-aware navigation, responsive and keyboard-friendly controls
- **Algorithms in the browser:** a live metaheuristic (HBALS) solving Traveling Salesman Problem instances, with animated visualization
- **Tools:** HTML5, CSS3, JavaScript, GitHub Pages

## Project structure

```
ErfanKhadiv.github.io/
├── index.html              # the whole page: styles, content and scripts
├── assets/
│   └── img/                # thumbnails, certificates and photos
├── docs/
│   └── screenshots/        # preview images used in this README
├── icon.svg                # site icons
├── favicon.ico
├── apple-touch-icon.png
├── icon-192.png
├── icon-512.png
├── .nojekyll               # tells GitHub Pages to serve the files as they are
└── README.md
```

## Setup and running

No installation is needed. Open `index.html` in a browser, or serve the folder locally:

```
git clone https://github.com/ErfanKhadiv/ErfanKhadiv.github.io.git
cd ErfanKhadiv.github.io
python3 -m http.server
```

Then visit `http://localhost:8000`.

## Deployment

The site is hosted with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Related projects

- [HBALS-TSP](https://github.com/ErfanKhadiv/HBALS-TSP): code, data and paper for the algorithm shown on the site.

## License

All rights reserved. The text, photos and certificates on this site are personal content and may not be reused without permission.
