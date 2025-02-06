# Nearest-Pharmacy


This project demonstrates how to use **Neo4j** and **OSMnx** to locate pharmacies in a city and find the nearest one to a given location. The project includes data extraction, database insertion, and distance calculation between points of interest.

## Features

- **Data Extraction**: Download and filter pharmacy data from OpenStreetMap for a specified city.
- **Database Integration**: Insert pharmacy data into a Neo4j database.
- **Distance Calculation**: Compute distances between the current location and pharmacies.
- **Visualization**: Display pharmacies and routes on an interactive map using Folium.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/safaeOulaja/Neo4jPharmacyFinder.git
   cd Neo4jPharmacyFinder
pip install osmnx geopandas neo4j networkx geopy folium requests webbrowser
2.Set up Neo4j:

Install Neo4j and start the server.
Update the uri, user, and password in the script to match your Neo4j credentials.
## Contributors
-[Benelfqih Aya](https://github.com/abenelfqih)
-[Safae Oulaja](https://github.com/safaeOulaja)
-[Errazouki Aya](https://github.com/AErrazouki)
