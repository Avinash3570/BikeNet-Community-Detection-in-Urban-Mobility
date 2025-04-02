# Helsinki City Bikes: Network Analysis

## Overview
This project analyzes the Helsinki city bike system through the lens of complex network theory. The study examines the bike-sharing system as a dynamic network where stations represent nodes and trips between them form the edges. By leveraging graph theory and network analysis techniques, we aim to uncover insights about the structure, efficiency, and usage patterns of the bike-sharing network.

## Project Goals
- Understand the network structure of the Helsinki bike-sharing system.
- Identify key stations and frequently used routes.
- Analyze network centrality measures to detect hubs and bottlenecks.
- Study the evolution of the network over time to determine trends in bike usage.

## Dataset
The dataset consists of bike trip records from Helsinki's public bike-sharing system. It includes information such as:
- **Trip start station**
- **Trip end station**
- **Timestamp of departure and arrival**
- **Trip duration**

## Methodology
1. **Data Cleaning & Preprocessing**: Removing inconsistencies and handling missing values.
2. **Graph Construction**: Representing stations as nodes and trips as weighted edges.
3. **Network Analysis**: Calculating key network metrics such as:
   - Degree Centrality
   - Betweenness Centrality
   - Clustering Coefficients
4. **Visualization**: Generating network graphs to represent bike movement patterns.

## Key Findings
- The network is highly decentralized, with key hubs near business and tourist centers.
- Certain stations act as critical connectors, facilitating mobility between districts.
- Bike demand fluctuates seasonally and varies based on time of day and day of the week.

## Technologies Used
- Python (pandas, networkx, matplotlib, seaborn)
- Jupyter Notebook
- Geospatial libraries (GeoPandas, Folium)
- Louvain Algorithm
- Girvan-Newman Algorithm

## License
This project is licensed under the MIT License.
