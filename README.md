# Digantara_solution



Satellite Position Tracker:This repository contains Python code to track the position of satellites using Two-Line Element (TLE) data and convert their Earth-Centered, Earth-Fixed (ECEF) coordinates to Latitude, Longitude, and Altitude (LLA). The tracked satellite data is then filtered based on specified geographical regions.

Table of Contents:
-Installation
-Usage
-Example
-Dependencies


1)Installation:
To run this code, you'll need to install the required Python packages. Use the following command:
https://github.com/vamsiwillbe/Digantara_solution.git


2)Usage:
The main script in this repository tracks satellite positions using TLE data, converts the coordinates, and filters the data based on specified regions. The code is designed to be run in Google Colab.


-Clone this repository:git clone https://github.com/vamsiwillbe/Digantara_solution.git
a.Upload the TLE file (30sats.txt in the example) to your Google Colab environment.
b.Open the main notebook satellite_position_tracker.ipynb in Google Colab.
c.Run the notebook cells to execute the code.

3)Example:
In the notebook, you'll find an example of how to use the code with sample TLE data. The script generates a CSV file (satellite_state_vectors.csv) containing satellite position information and converts it to Latitude, Longitude, and Altitude.


4)Dependencies

sgp4: Python implementation of the SGP4 model for satellite orbit prediction.
pyproj: Python interface to PROJ (cartographic projections library).
pandas: Data manipulation and analysis library.


