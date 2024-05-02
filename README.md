# ML-examples

# Example2: Image Clustering with K-Means Algorithm
This Python script performs image clustering using the K-Means clustering algorithm. It takes an input image and the desired number of clusters (k) as parameters and returns the clustered image along with the inertia, which is the sum of squared distances of points to their cluster centers. Also it displays a color palette from the unique colors present in a processed image.

## Requirements
* Python 3.x
* NumPy
* scikit-learn
* matplotlib

# Example3: Exoplanets Orbital Data Visualization and Clustering
Data were retrieved from the NASA Exoplanet Archive [ExoTbls](https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS).

## Interactive Scatter Plot of Orbital Period vs. Semi-Major Axis
This visualization explores the relationship between a celestial body's orbital period and its semi-major axis (a measure of its orbit's size). 
The chart is created using the `altair` library and allows for interactivity (hovering over points reveals details).

## Exoplanet Density vs Mass
Data can be clustered in two groups: dense and small rocky planets, and less dense giants. 
