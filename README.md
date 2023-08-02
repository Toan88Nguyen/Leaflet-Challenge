# Leaflet-Challenge

## Background

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, I have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

# Instructions

The instructions for this activity are broken into two parts:

- Part 1: Create the Earthquake Visualization

- Part 2: Gather and Plot More Data (Optional with no extra points earning)

# Part 1: Create the Earthquake Visualization

![image](https://github.com/Toan88Nguyen/Leaflet-Challenge/assets/120751287/01a001d0-7124-4ec1-b106-69e4be11ae53)

My first task is to visualize an earthquake dataset. Complete the following steps:

1. Get my dataset. I do the follow these steps:

    - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON FeedLinks to an external site](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) and choose a dataset to visualize. The following image is an example screenshot of what appears when I visit this link:

![image](https://github.com/Toan88Nguyen/Leaflet-Challenge/assets/120751287/6c8aa4fd-a8ce-4a51-89bd-0a3a10e9fe42)

  - When I click a dataset (such as "All Earthquakes from the Past 7 Days"), I will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

![image](https://github.com/Toan88Nguyen/Leaflet-Challenge/assets/120751287/a82bedb3-9c91-458e-86ef-c73d1cfc8a93)

2. Import and visualize the data by doing the following:

    - Using Leaflet, create a map that plots all the earthquakes from my dataset based on their longitude and latitude.

      - My data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

      - Hint: The depth of the earth can be found as the third coordinate for each earthquake.

    - Include popups that provide additional information about the earthquake when its associated marker is clicked.

    - Create a legend that will provide context for your map data.

    - My visualization should look something like the preceding map.

# Part 2: Gather and Plot More Data (Optional with no extra points earning)

Plot a second dataset on my map to illustrate the relationship between tectonic plates and seismic activity. I will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at [https://github.com/fraxen/tectonicplatesLinks](https://github.com/fraxen/tectonicplates). 

This part is completely optional; I can complete this part as a way to challenge yourself and boost your new skills.

The following image is an example screenshot of what you should produce:

![image](https://github.com/Toan88Nguyen/Leaflet-Challenge/assets/120751287/979f59c7-5b06-41f3-9d8a-b9b62ddb89d9)

Perform the following tasks:
  
  - Plot the tectonic plates dataset on the map in addition to the earthquakes.
  
  - Add other base maps to choose from.

  - Put each dataset into separate overlays that can be turned on and off independently.

  - Add layer controls to your map.

# End
