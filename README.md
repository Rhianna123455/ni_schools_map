# NI Schools Map
EGM722 Assignment

Rhianna Wilkinson - B00840795

## Project Aim
This project creates an interactive map of school locations across Northern Ireland. The aim is for the map to visually represent different types of schools and calculate the distance from a user defined location to each school.  The map will be created using Python within a Jupyter Notebook, utilising Pandas, Folium and Geopy.

## Features
- Interactive Folium Map
- Display of user location
- Display of school locations
- Classification of school types into categories
- Toggle Fiter to show or hide different school categories
- Pop up to appear when each school marker is clicked
- Calculates distance from a user defined location and included within pop up
- 5km buffer surrounding user location to visualise nearby schools
- Exportable HTML map for external viewing

## Software and Libraries 
- Python
- Pandas
- Folium
- Geopy
- Jupyter Notebook

## Requirements
To run this project, the following software must be installed:

- Git - to clone the repository
- Anaconda - to access Juypter Notebook
  
## How to Complete This Project
Step 1: Clone the repository:

Clone this repository using this link: 
git clone https://github.com/yourusername/ni_schools_map.git

Step 2: Navigate to the project folder:
cd ni_schools_map

Step 3: Create the environment:
conda env create -f environment.yml

Step 4: Activate the environment:
conda activate schools_env

Step 5: Open the notebook:
jupyter notebook

Step 6: Run all cells to generate the map
