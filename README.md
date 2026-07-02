# OneBill CPQ — Diagnostic Imaging Sample Product Model

Shareable site for the OneBill technical team. It hosts the CPQ product-requirements briefs and interactive product catalogs for a capital diagnostic-imaging portfolio (CT, MRI, X-Ray), authored by EasyQ2C Product Management.

## Live site

Once GitHub Pages finishes its first deploy: **https://pratim-easyq2c.github.io/OneBillCPQ-sampleProduct/**

## Contents

| Path | Description |
|------|-------------|
| `index.html` | Landing page linking to every document |
| `v2/requirements-brief.html` | CPQ Product Requirements Brief (EQ2C-DI-CATALOG-001) |
| `v2/product-catalog.html` | Interactive product catalog (EQ2C-DI-CATALOG-001) |
| `v3/requirements-brief.html` | Requirements brief, Conga demo-aligned (EQ2C-DI-CATALOG-003) |
| `v3/product-catalog.html` | Product catalog, Conga demo-aligned (EQ2C-DI-CATALOG-003) |

Each HTML file is fully self-contained — catalog CSVs and images are embedded, and the CSVs can be downloaded from within the catalog pages. No build step or external assets are required.

## Deployment

Pushing to `main` triggers `.github/workflows/deploy-pages.yml`, which enables (on first run) and deploys GitHub Pages automatically.

> Product and vendor names (Helix, Meridian, Apex, EasyQ2C) are illustrative and used for demonstration only.
