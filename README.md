# Professional Portfolio

A public portfolio showcasing selected data engineering, cloud, analytics, and software projects, with an emphasis on architecture, engineering decisions, implementation, and practical outcomes.

**Live site:** https://jhasoon.github.io/

**Featured project:** https://jhasoon.github.io/projects/fmdx-aws/

## What this repository contains

This repository contains the **Astro source code** for the portfolio website, its styling and reusable components, and approved public showcase assets such as architecture diagrams. GitHub Actions builds and deploys the site to GitHub Pages.

Engineering implementations, datasets, and detailed project documentation are maintained in **separate private repositories**. Only selected, reviewed material is published here.

## Technology

- **Astro:** Static website generation and component-based pages
- **HTML and CSS:** Responsive presentation and styling
- **Node.js and npm:** Local development and reproducible builds
- **Git and GitHub:** Source control and collaboration history
- **GitHub Actions:** Automated build and deployment
- **GitHub Pages:** Public static website hosting
- **SVG:** Scalable architecture and data-flow diagrams

Astro was selected to provide a lightweight, maintainable static website without requiring a continuously running application server.

## Featured work

### FMDX — AWS Data Platform

A cloud data engineering showcase covering ingestion, medallion data processing, orchestration, historical dimensional modelling, data quality, and analytical consumption through AWS Athena and Power BI.

[Explore the FMDX AWS showcase](https://jhasoon.github.io/projects/fmdx-aws/)

## Local development

Requires a compatible Node.js version and npm.

```bash
npm ci
npm run dev
```

To validate the production build:

```bash
npm run build
npm run preview
```

## Deployment

A push to the `main` branch triggers the workflow at `.github/workflows/deploy.yml`, which builds the Astro site and publishes the generated `dist/` directory to GitHub Pages.

```bash
npm run build
git status
git add <reviewed-files>
git commit -m "Describe change"
git push origin main
```

Review changes before committing or publishing. The published site is publicly accessible.

## Project scope

This is a presentation repository, **not** a mirror of the underlying engineering project repositories. The portfolio evolves as additional projects become ready for public demonstration.
