# Accident-Hotspot-Analysis
# Description
Developed an accident hotspot analysis system using real-world traffic accident data from the Vizag region to identify high-risk accident-prone locations. Performed data preprocessing and geospatial analysis using Python, Pandas, and NumPy, and applied clustering algorithms with Scikit-learn to detect accident hotspots based on latitude and longitude coordinates. Visualized the identified hotspots on an interactive map using Folium and Leaflet, enabling easy exploration of accident-prone zones. This system supports traffic safety analysis and assists in data-driven decision-making for accident prevention.

# Features 
1. Accident hotspot detection using clustering
2. Interactive map visualization
3. Traffic data analysis

# Tech Stack
Python, Pandas, NumPy, Scikit-learn, Folium, Jupyter Notebook

# project structure

Accident-Hotspot-Analysis/
│

├── vizag_5000.csv

│   → Traffic accident dataset containing latitude and longitude of accident locations.

│

│

├── Clustering.ipynb

│   → Accident hotspot detection using clustering algorithms.

│      - Groups accident locations based on geographical proximity

│      - Identifies high-risk accident-prone zones (hotspots)

│      - Generates cluster centers

│
├── Hotspots.html

│   → Interactive map visualization of detected accident hotspots.

│      - Displays clustered hotspot locations

│      - Allows zooming and exploration of accident-prone areas

│
└── README.md
    → Project documentation and usage instructions.
    


# How to run the project
1. Install dependencies
2. Run Jupyter Notebook
3. Open Clustering.ipynb
4. Run all cells
5. Open Hotspots.html to view map

# Output
- Clustered accident-prone locations
- Interactive hotspot map
- Accident risk zones

