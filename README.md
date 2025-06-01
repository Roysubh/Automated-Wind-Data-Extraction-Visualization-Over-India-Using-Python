🌀 Automated Wind Data Extraction, Visualization Over India Using Python

📝 Overview:
  This project automates the process of extracting, clipping, visualizing, and animating wind datasets (10m u and v components) over India using Python. It provides a seamless workflow for working with NetCDF climate data, shapefiles, and geospatial visualization. Ideal for climate analysts, researchers, students, and GIS professionals interested in Indian regional wind patterns.

🚀 Features:
  ✅ Load 10m wind component data (u10, v10) from NetCDF
  ✅ Clip wind data to India's administrative boundary shapefile
  ✅ Compute wind speed and direction
  ✅ Plot:
    Wind speed maps
    Wind vector fields
  ✅ Generate high-quality PNG outputs
  ✅ 🎞️ Create animated wind maps (GIF format)
  ✅ Easily customize for other countries or datasets

📦Required Python Libraries:
  xarray, netCDF4 – NetCDF data handling
  rasterio – GeoTIFF export (optional)
  matplotlib, imageio – Plotting and animation
  cartopy – Geospatial plotting
  geopandas, shapely – Shapefile operations
  os, glob, datetime – File and time utilities

🗺️ India Shapefile Sources
  You can download official shapefiles of India’s boundary from these sources:
  🌍 GADM – Global Administrative Boundaries
  🌐 OpenDataSoft India Boundaries
  🛰️ ISRO Bhuvan Geoportal
  🗺️ Survey of India (SOI) (may require login)

📊 Steps to Run the Project
  1. Load Wind Data
  Place your wind NetCDF file (u10, v10 components) in the data/ directory.
  
  2. Run the Notebook
  Open Wind.ipynb in Jupyter and run all cells:
  Load wind and shapefile data
  Clip wind data to India's shape
  Compute wind speed
  Plot and save
  Wind speed map
  Wind vector field
  Generate animation over time using imageio or matplotlib.animation

✅ Applications
  Meteorological studies
  Environmental modeling
  Climate research
  Disaster preparedness (wind hazard zones)
  Educational and academic purposes

🧠 Conclusion
  This project streamlines the wind data workflow over India—from raw NetCDF extraction to professional-grade static and animated outputs. 
  It is modular, customizable, and ready for scaling to other regions or datasets.


