# Caretta Caretta Nesting Sites Map

This project visualizes nesting sites of the loggerhead sea turtle (*Caretta caretta*) in Greece using spatial data extracted from an RDF graph.

## Project Overview

- Create a data pipeline to extract geographic data from RDF sources.
- Convert geometries to a standard coordinate system (WGS84).
- Visualize the locations on an interactive map using Folium.

## Features

- RDF parsing and geometry extraction.
- Interactive web map with layered controls.

## Tools Used

- Python
- `rdflib` for RDF parsing
- `pandas` and `geopandas` for data manipulation
- `folium` for map visualization

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/akprodromou/caretta-caretta-map.git
    ```

2. Set up a virtual environment and install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook to generate the map.

