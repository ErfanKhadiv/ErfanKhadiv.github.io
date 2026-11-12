# Erfan Khadiv — Personal Portfolio

Personal portfolio of Erfan Khadiv, a Computer Engineering graduate building toward AI research, with interests in algorithms, combinatorial optimisation, machine learning and software development.

**[Visit the portfolio](https://erfankhadiv.github.io/)** · **[Official HBALS research website](https://erfankhadiv.github.io/HBALS-TSP/)** · **[GitHub](https://github.com/ErfanKhadiv)** · **[LinkedIn](https://www.linkedin.com/in/erfan-khadiv-777a66279/)**

## Portfolio focus

The personal site is intentionally an overview rather than a second copy of the full HBALS research lab. It introduces the author and links to the dedicated HBALS v2 website for the complete method, benchmark tables, statistical analysis, ablation, saved convergence data, interactive demo and reproducibility materials.

## Profile highlights

- B.Sc. Computer Engineering, Islamic Azad University, Ardabil Branch
- GPA: **18.05/20** · certified graduate rank: **4th**
- Average across six core CS courses: **19.7/20**
- IELTS Academic: **8.0** (L 8.5 · R 9.0 · W 7.0 · S 6.5)
- Sole-author preprints: HBALS v2 (TSP optimisation) and a critical Li-Fi review
- 120-hour IT and networking internship at the Ports and Maritime Organization of Iran

## Research

### HBALS v2

A Hybrid Bees Algorithm with 2-opt Local Search for the Travelling Salesman Problem. The v2 study covers 15 TSPLIB instances, equal move-evaluation budgets, six comparison methods on the main set, a seven-variant ablation, non-parametric statistical testing and independent run-by-run verification.

Across the 12 main instances, HBALS achieved the best average rank (**1.25 of six**) and a mean gap of **0.299%** to the best-known solutions. It was significantly better than four comparison methods after Holm correction; its overall difference from ILS-2opt was not statistically significant. The preprint is not peer reviewed; the manuscript was submitted to *Croatian Operational Research Review*.

- [Official HBALS research website](https://erfankhadiv.github.io/HBALS-TSP/)
- [Source code and experiment data](https://github.com/ErfanKhadiv/HBALS-TSP)
- [Zenodo preprint](https://doi.org/10.5281/zenodo.23621275)

### Li-Fi critical review

A sole-authored review of Li-Fi operating principles, modulation, standards and performance claims. The Zenodo preprint was submitted to *Wireless Personal Communications* (Springer) on 4 November 2026; it has not yet been peer reviewed.

- [Zenodo preprint](https://doi.org/10.5281/zenodo.23898313)
- [GitHub report](https://github.com/ErfanKhadiv/LiFi-Report)

## Selected projects

- **Workfolio:** browser-based resume builder with five templates, live preview and an on-device AI job-matching tool.
- **CS50AI:** implementations of all twelve problem sets from Harvard's Introduction to AI with Python.
- **Kouman:** bilingual Persian/English e-commerce front end built with React, React Router and Vite.
- **Python fundamentals:** small applications covering JSON persistence, OOP and NumPy analysis.

## Site features

- English and Persian language switch, including RTL layout
- Dark and light themes
- Responsive single-page layout
- Research gateway to the dedicated HBALS website
- Selected projects, education, academic highlights, skills and networking experience
- Downloadable two-page CV
- Handwritten signature in the copyright footer

## Project structure

```text
ErfanKhadiv.github.io/
├── index.html
├── assets/
│   ├── Khadiv_Erfan_CV.pdf
│   ├── docs/
│   │   └── Bee_Algorithm_Presentation.pdf
│   └── img/
│       ├── erfan-signature-gold.png
│       ├── research/
│       │   ├── hbals-v2-ablation.png
│       │   ├── hbals-v2-anytime.png
│       │   └── hbals-v2-boxplots.png
│       └── ...
├── icon.svg
├── favicon.ico
├── README.md
└── .nojekyll
```

## Run locally

No build step is required. Open `index.html` directly or serve the folder with a static HTTP server:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deployment

The site is designed for GitHub Pages from the repository root (`/`). Commit the updated files to the `main` branch and keep the Pages source set to **Deploy from a branch → main → /(root)**.
