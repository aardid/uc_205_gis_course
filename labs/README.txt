ENCN205 — GIS Labs (Lab 0 to Lab 3), self-contained package
=============================================================

Work through the labs in order. For each lab:
  1. Read the Instructions (HTML)
  2. Complete the Jupyter notebook (.ipynb)
  3. Pass the sign-off quiz on LEARN and upload the generated PNG there

Contents
--------
  Lab0_Instructions.html      Environment installation guide (start here)
  Lab0_Setup.ipynb            Environment check + first map (ungraded)

  Lab1_Instructions.html
  Lab1_SpatialData_CRS.ipynb  Reading, exploring, projecting spatial data

  Lab2_Instructions.html
  Lab2_VectorAnalysis.ipynb   Vector analysis (buffers, joins, overlays)

  Lab3_Instructions.html
  Lab3_RasterAnalysis.ipynb   Raster analysis (DEM, slope, hazards)

  data/                       Datasets used by the notebooks
    christchurch.gpkg           (Lab 2)
    banks_peninsula_dem.npy     (Lab 3)
    banks_peninsula_meta.json   (Lab 3)

Requirements
------------
Python >= 3.10 with JupyterLab and the conda-forge packages listed in
Lab0_Instructions (geopandas, pandas, numpy, matplotlib, shapely, pyproj,
pyogrio, fiona, folium, geodatasets). Lab 0 checks all of this for you.

Keep this folder structure intact — the notebooks look for their data in
the ./data subfolder. Run Jupyter from this folder.

Note: a few optional cells need an internet connection (Natural Earth
download in Lab 1, interactive folium maps). Everything else runs offline.
