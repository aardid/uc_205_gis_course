# ENCN205 — GIS Component: Lecture Slides & Interactive Demos

Backup copy of the lecture slides (PDF) and interactive demos for ENCN205 (Applied Data Analysis for Civil and Natural Systems, University of Canterbury), GIS component, 2026.

**Live site:** https://aardid.github.io/uc_205_gis_course/

Each demo is a single self-contained HTML file. The `data/` folder holds the spatial data as JavaScript, and `lib/leaflet/` holds the Leaflet library, so the demos work without an internet connection apart from the optional basemap tiles.

| File | Lecture |
|---|---|
| `L01_LayerExplorer.html` | 1 — Why Location Matters |
| `L02_DataQuality.html` | 2 — Data Quality & Ethics |
| `L03_VectorRaster.html` | 3 — Spatial Data Models |
| `L04_CRS_Explorer.html` | 4 — CRS & Projections |
| `L05_SpatialQueries.html` | 5 — Spatial Relationships |
| `L06_VectorAnalysis.html` | 6 — Vector Analysis |
| `L07_MapStyling.html` | 7 — Cartography Essentials |
| `L08_RasterAnalysis.html` | 8 — Raster Analysis |
| `L09_FlowAnalysis.html` | 9 — Hydrological Analysis |
| `L10_RiskAssessment.html` | 10 — Risk Assessment & MCE |
| `_L11_ClaudeCodeMapDemo.html` | 11 — The Future of GIS |

To use offline: download the repository as a ZIP (green **Code** button → *Download ZIP*), unzip, and open any `L*.html` file in a browser.

## Lecture slides

PDF exports of the lecture decks (slides only, no speaker notes) live in `lectures/`.

| File | Lecture |
|---|---|
| `lectures/Lecture01_WhyLocationMatters.pdf` | Lecture 1 — Why Location Matters |
| `lectures/Lecture02_DataQualityEthics.pdf` | Lecture 2 — Data Quality & Ethics |
| `lectures/Lecture03_SpatialDataModels.pdf` | Lecture 3 — Spatial Data Models |
| `lectures/Lecture04_CRS_Projections.pdf` | Lecture 4 — CRS & Projections |
| `lectures/Lecture05_SpatialRelationships.pdf` | Lecture 5 — Spatial Relationships |
| `lectures/Lecture06_VectorAnalysis.pdf` | Lecture 6 — Vector Analysis |
| `lectures/Lecture07_CartographyEssentials.pdf` | Lecture 7 — Cartography Essentials |
| `lectures/Lecture08_RasterAnalysis.pdf` | Lecture 8 — Raster Analysis |
| `lectures/Lecture09_HydrologicalAnalysis.pdf` | Lecture 9 — Hydrological Analysis |
| `lectures/Lecture10_RiskAssessmentMCE.pdf` | Lecture 10 — Risk Assessment & MCE |
| `lectures/Lecture11_FutureOfGIS.pdf` | Lecture 11 — The Future of GIS |

## Updating

The source of truth is the course project folder (`Demos/ENCN205_Demos_SelfContained/`). To publish a new version, copy that folder's contents over this repository. Lecture PDFs come from `Lectures/Lecture_pdf/` and go in `lectures/`. Then commit and `git push origin main main:gh-pages`.
