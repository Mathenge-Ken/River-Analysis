# Flood Analysis Using Python🌊 🌍 

## Project Overview
This project focuses on analyzing river dynamics and flood risks using Python. By creating a Relative Elevation Model (REM) from Digital Elevation Models (DEMs), we visualize and understand how elevation changes can impact flood behavior. The analysis leverages various Python libraries to manipulate geospatial data, perform interpolation, and visualize results effectively. For a deeper understanding of river dynamics analysis, check out this article: [Effortless River Dynamics Analysis: Mastering Flood Modeling with Just 30 Lines of Python](https://mathengeken.hashnode.dev/effortless-river-dynamics-analysis-mastering-flood-modeling-with-just-30-lines-of-python).

## Key Activities
1. **Setup Environment**: 
   - Created a virtual environment using Anaconda to manage dependencies.
   - Installed necessary libraries such as `numpy`, `pandas`, `geopandas`, `matplotlib`, `rioxarray`, `osmnx`, and `xarray`.

2. **Load Digital Elevation Models (DEMs)**:
   - Accessed and loaded DEM data from USGS for the analysis area.

3. **Geocode River Geometry**:
   - Utilized the `osmnx` library to geocode the Mississippi River and extract its geometry for analysis.

4. **Sample and Interpolate Elevation Data**:
   - Employed nearest neighbor sampling to obtain elevation values along the river.
   - Used KD-trees for efficient spatial querying and interpolation of elevation data.

5. **Calculate Relative Elevation Model (REM)**:
   - Subtracted interpolated elevation values from the cropped DEM to derive the REM.

6. **Visualize Results**:
   - Created hillshade representations of the DEM.
   - Applied color shading to the REM for enhanced visualization.
   - Stacked the hillshade and REM images into a composite visualization.
   - Saved the final visualization as an image file.

## Skills Learned  📕 
- **Data Manipulation**: Gained proficiency in using `numpy` and `pandas` for handling and processing geospatial data.
- **Geocoding**: Learned how to extract geographical features using the `osmnx` library.
- **Spatial Interpolation**: Developed skills in interpolating spatial data with KD-trees, enhancing accuracy in elevation estimates.
- **Visualization Techniques**: Mastered techniques for visualizing raster data using `matplotlib` and `geopandas`, including shading and hillshading methods.
- **Working with Digital Elevation Models (DEMs)**: Acquired knowledge in creating, manipulating, and analyzing DEMs for hydrological studies.

## Conclusion
This project provided valuable insights into flood analysis using Python, demonstrating how coding can facilitate complex geographical analyses. The skills acquired will serve as a strong foundation for further exploration in spatial data science and hydrology.
