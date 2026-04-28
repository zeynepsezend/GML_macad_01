# Assignment 01 - Graph Machine Learning for MACAD

This repository contains the first assignment for the Graph Machine Learning (GML) course, focusing on Multi-Agent Connected Autonomous Driving (MACAD). The assignment covers various topics in graph theory, spatial representations, and machine learning applications on graphs.

## Contents

### Notebooks
- **S02-01 Primal vs Dual.ipynb**: Introduction to primal and dual graph representations
- **S02-02 Metric vs Topological.ipynb**: Comparison of metric and topological spaces in graphs
- **S02-03 Adjacency Vs Access.ipynb**: Understanding adjacency matrices versus accessibility in graphs
- **S02-04 Geometric Representations.ipynb**: Geometric aspects of graph representations
- **S02-05 Spatial Representations.ipynb**: Spatial intelligence and representations
- **S02-06 Importing OBJ files.ipynb**: Working with OBJ file formats for 3D models
- **S03-07 Spatial Intelligence Part 1.ipynb**: Advanced spatial intelligence concepts
- **S03-08 Spatial Intelligence Part 2.ipynb**: Continued exploration of spatial intelligence
- **S03-09 Spatial Intelligence Part 3.ipynb**: Final part on spatial intelligence
- **S04-10 A. IFC Semantic Relationships.ipynb**: Industry Foundation Classes (IFC) semantic relationships
- **S04-11 B. IFC Spatial Relationships.ipynb**: IFC spatial relationships
- **S05-12 Dataset and Feature Engineering.ipynb**: Data preparation and feature engineering for GML
- **S06-13 GML Graph Classification.ipynb**: Graph classification using machine learning
- **S06-14 GML Graph Regression.ipynb**: Graph regression tasks
- **S06-14 GML Regression.ipynb**: Additional regression notebook
- **S06-15 GML Node Classification.ipynb**: Node classification in graphs
- **S07-14 Neo4j Tutorial 1.ipynb**: Introduction to Neo4j graph database

### Supporting Files
- **Supporting Files/**: Contains datasets, IFC files, and other resources
  - `gallery.brep`: BREP file for geometric modeling
  - `Ifc2x3_Duplex_Architecture.ifc`: IFC model file
  - `dataset_graph_classification/`: Dataset for graph classification tasks
  - `dataset_graph_regression/`: Dataset for graph regression tasks
  - `dataset_node_classification/`: Dataset for node classification tasks
  - `dataset_node_classification_500/`: Larger node classification dataset

## Requirements

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages (install via pip):
  - numpy
  - pandas
  - matplotlib
  - networkx
  - torch
  - torch-geometric (if applicable)
  - scikit-learn
  - Other packages as needed by specific notebooks

## Installation

1. Clone this repository
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt  # If a requirements.txt is provided
   ```
   Or install packages as needed when running notebooks.

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the desired notebook file
3. Run cells in order

## Dataset Information

The datasets provided are for educational purposes and contain graph-structured data for various machine learning tasks including classification and regression on graphs and nodes.

## Contributing

This is an assignment repository. For questions or issues, please contact the course instructor.

## License

This project is for educational purposes as part of the GML_MACAD course.