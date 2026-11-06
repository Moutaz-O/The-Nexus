# THE NEXUS — Visual Assets

This folder is reserved for the full-resolution branded photography and project cover illustrations.

The website currently contains working, resolution-independent vector fallbacks. Uploading images to this folder using the filenames below automatically activates the photographic artwork without changing the site code:

- `hero-cover.webp` — original founder cover (Home)
- `project-01.webp` — Hospital Operations & Capacity
- `project-02.webp` — Diabetes Care Quality
- `project-03.webp` — CKD Monitoring
- `project-04.webp` — Clinical Trial & RCT Analysis
- `project-05.webp` — Readmission & Patient Safety
- `project-06.webp` — Healthcare Financial Performance

## Important

These are **illustrative branding images**. Dashboard numbers that appear in AI-generated cover images are fictional decorative examples and must not be presented as analysis outcomes. The project's actual results must come from verified notebooks, SQL and dashboards.

The official high-quality emblem is a separate vector at `../nexus-symbol.svg`; the website should not scale up a 265px raster copy.

## Upload on GitHub

Open this folder on GitHub, select **Add file → Upload files**, drop all seven optimized WebP files, and choose **Commit changes**. GitHub Pages will publish them automatically when deployment completes.

CSS and site.js already reference these filenames, and include SVG fallbacks while images are missing.