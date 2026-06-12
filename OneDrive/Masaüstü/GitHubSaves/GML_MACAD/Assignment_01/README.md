# Assignment 01 - Graph Machine Learning for MACAD

This repository contains the first assignment for the Graph Machine Learning (GML) course, focusing on Multi-Agent Connected Autonomous Driving (MACAD). The assignment covers various topics in graph theory, spatial representations, and machine learning applications on graphs.

## Contents
- house.obj
- windows.obj
- doors.obj
- gitignore
- README
- ZeynepSezenDursun_01.ipynb

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