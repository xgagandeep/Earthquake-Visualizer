
# Earthquake Data Visualizer 🌍

**Project:** Earthquake Data Visualizer  
**Date:** January 2019  
**Language:** Python  
**Tools/Libraries:** Matplotlib, Basemap, mplcursors, IPython, pandas, ipywidgets  
**Type:** Interactive Map Visualization

## Overview

This project is an interactive map-based visualizer that plots real-time earthquake data from the USGS (United States Geological Survey). It displays earthquakes from around the world, based on their magnitude and location. The project provides an intuitive way to explore seismic activity, using an interactive map that updates the details when you hover over different earthquake points.

## Features

- **Interactive Map:** Displays a Mercator-projection map of the world, showing the locations of recent earthquakes.
- **Real-Time Data:** Pulls the latest earthquake data from the USGS in real-time (data source: [USGS Earthquake API](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_month.csv)).
- **Magnitude-Based Sizing:** Each earthquake's size on the map is proportional to its magnitude.
- **Hover Annotations:** Hovering over earthquake points shows detailed information, including location, magnitude, and time of the event.
- **Interactive Update Button:** Allows you to manually update the visualization with the latest earthquake data.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/xgagandeep/earthquake-data-visualizer.git
   cd earthquake-data-visualizer
   ```

2. Install the required libraries:
   ```bash
   pip install matplotlib basemap mplcursors pandas ipywidgets
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook EarthquakeDataVisualizer.ipynb
   ```

4. Interact with the map by hovering over earthquake points to see more details, or click the **Update** button to fetch new data.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: Matplotlib, Basemap, mplcursors, pandas, ipywidgets

## About

This was my very first project in Python, originally completed in January 2019. At the time, it was posted on a different GitHub repository, but since I no longer manage that, I am moving it here with a proper README. This project was a learning experience in data visualization and handling real-time data. 

Feel free to explore, provide feedback, or contribute!

## License

This project is open-source under the MIT License.
