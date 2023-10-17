# Network Science Project - Exploring Development Funds Flow

This repository contains the code and report for a Network Science project focused on exploring the flow of development funds using Official Development Assistance (ODA) data collected by the Organisation for Economic Co-operation and Development (OECD).

## Code Structure
The code is organized as a Jupyter notebook (Network_Science_Project.ipynb). It includes the following main sections:

### Data Preprocessing:
Loading and preprocessing the ODA data from the QWIDS dataset.
Creating directional graphs for each year.

### Community Detection:
Using Louvain algorithm to detect communities within the graphs.
Mapping the communities onto a world map for visualization.

### Centrality measures:
Applying the Linkcom algorithm for community detection.
Saving the resulting graph in GEXF format.

## Running the Code
Open the Jupyter notebook Network_Science_Project.ipynb in a suitable environment (e.g., Jupyter, Google Colab).
Run each cell in sequential order.

## Future Work
The project has identified potential areas for improvement and future research. These include exploring more robust ways of community detection, considering Other Official Flows (OOF) and Private funds, expanding the analysis to include public and private organizations, and conducting sector-specific analyses.
