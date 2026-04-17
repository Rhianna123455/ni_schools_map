# NI Schools Interactive Map
EGM722 Assignment

Rhianna Wilkinson - B00840795

## Project Aim
This project creates an interactive map of school locations across Northern Ireland. The aim is for the map to visually represent different types of schools and calculate the distance from a user defined location to each school.  The map will be created using Python within a Jupyter Notebook, utilising Pandas, Folium and Geopy.

## Features
- Interactive Folium Map
- Display of user location
- Display of school locations
- Classification of school types into categories
- Toggle Filter to show or hide different school categories
- Pop up to appear when each school marker is clicked
- Calculates distance from a user defined location and included within pop up
- 5km buffer surrounding user location to visualise nearby schools
- Exportable HTML map for external viewing

## Tools and Libraries 
- Python
- Pandas
- Folium
- Geopy
- Jupyter Notebook

## Requirements
To run this project, the following software must be installed:

- Git (to clone the repository)
- Anaconda (to access Juypter Notebook)

## Data
The data utilised within this project is contained within the data folder within the repository, however if the user wants to explore the original dataset further it can be access using OpenDataNI within the Education Section called School Locations (https://admin.opendatani.gov.uk/dataset/39cd6af4-8fed-4ac9-9620-577a2190bb34/resource/d0947faf-5d84-4ce4-80dd-ce4fa0e1c0d5/download/locate-a-school-open-data-feb-2016.csv).
  
## How to Run This Project
Step 1: Clone the repository:

Clone this repository using git clone following this link: https://github.com/Rhianna123455/ni_schools_map 

Step 2: Navigate to the project folder:

Using Anaconda Prompt navigate to the project folder using the following code:

cd ni_schools_map

Step 3: Create the environment:

Within Anaconda prompt create the environment using the following code:

conda env create -f environment.yml

Step 4: Activate the environment:

Activate the environment within Anaconda using the following code:

conda activate schools_env

Step 5: Open the notebook:

Within Anaconda launch jupyter notebook and navigate to the schools_map.ipynb notebook and open it.

Step 6: Run all cells within the notebook to generate the interactive map
