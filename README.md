# Analysing OpenStreetMap road networks

## Description
This project was completed as part of the course Machine Learning on Graphs (CS224W). This course, originally held at Stanford University, was attended by us at the Faculty of Computer and Information Science in Ljubljana.

The main objective of the project was to address the problem of missing labels in road segments obtained from [OpenStreetMap](https://www.openstreetmap.org/) by representing the road networks as graphs and developing models that could predict road type, lane count, and speed limit.

## Code structure
The Jupyter notebook "ProjectMLG.ipynb" covers the entire data preparation pipeline, as well as the implementation and utilization of three Graph Neural Network methods:
- GCN (Graph Convolution Network)
- GraphSAGE
- GAT (Graph Attention Network)

In our example, we used the city of Ljubljana, but the code can be adapted to work with any other city by modifying the city name in the first OSM query.
