# Sebastian Kalhöfer — Personal Website

[![Deploy to GitHub Pages](https://github.com/Skalhoef/Sebastians_Homepage/actions/workflows/static.yml/badge.svg)](https://github.com/Skalhoef/Sebastians_Homepage/actions/workflows/static.yml)

A lightweight personal and academic website presenting my background, research interests, publications, scientific notes, and selected resources.

[View the live website](https://skalhoef.github.io/Sebastians_Homepage/)

## About the project

This website serves as my professional online presence. It introduces my work as a theoretical physicist and scientific programmer, with a focus on:

- Thermal quantum field theory
- Computational materials science
- Electron–phonon interactions
- Numerical modelling and scientific computing
- Data analysis and computational workflows

The research section also provides access to selected publications, presentations, derivations, and technical notes.

## Website sections

- **About** — Professional background and current interests
- **Research** — Research areas, publications, and scientific material
- **Collections** — Selected resources on computing and technology
- **Contact** — A privacy-conscious contact method

## Technologies

The website is intentionally lightweight and dependency-free:

- Semantic HTML5
- Responsive CSS
- GitHub Actions
- GitHub Pages

No JavaScript framework, build system, or external runtime is required.

## Run locally

Clone the repository:

```bash
git clone https://github.com/Skalhoef/Sebastians_Homepage.git
cd Sebastians_Homepage
```

Open `index.html` directly in a browser, or serve the directory locally:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deployment

Pushes to the `main` branch are automatically deployed to GitHub Pages through the workflow defined in [`.github/workflows/static.yml`](.github/workflows/static.yml).

## Repository structure

```text
.
├── .github/workflows/   # Automated GitHub Pages deployment
├── images/              # Images and graphical assets
├── notes/               # Scientific notes and presentations
├── index.html           # About page
├── Research.html        # Research and publications
├── Collections.html     # Curated resources
├── Contact.html         # Contact information
└── styles.css           # Shared website styling
```

## Author

**Sebastian Kalhöfer**  
PhD candidate in Theoretical Physics at Uppsala University

- [GitHub profile](https://github.com/Skalhoef)
- [Personal website](https://skalhoef.github.io/Sebastians_Homepage/)
