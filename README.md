# Graph Mining Node Classification

Graph mining course project focused on node classification in citation networks using graph neural network models.

This project explores how graph structure, node features, and neighborhood information can be used together to classify nodes in graph-based datasets.

The project compares two common graph neural network approaches:

- Graph Convolutional Network (GCN)
- GraphSAGE

---

## Project Overview

In citation networks, each node represents a document and each edge represents a citation or relationship between documents.

The goal of node classification is to predict the category of each node using:

- node feature vectors
- graph connectivity
- neighborhood structure
- learned node representations

This project studies graph-based learning methods on standard citation graph datasets.

---

## Why This Project Matters

This repository provides a machine learning and graph mining complement to my other embedded AI and physical-system projects.

While my other projects focus on sensor data, dynamic systems, estimation, and embedded deployment, this project shows experience with a more standard AI/CS topic:

```text
graph representation learning and node classification
```

The project is relevant to:

- graph mining
- graph neural networks
- node classification
- representation learning
- citation network analysis
- geometric deep learning

---

## Models Studied

### Graph Convolutional Network

GCN is a graph neural network model that updates node representations by aggregating information from neighboring nodes.

It is commonly used for semi-supervised node classification in citation graphs.

### GraphSAGE

GraphSAGE learns node representations by sampling and aggregating information from local neighborhoods.

It is designed to generalize representation learning to unseen nodes and larger graphs.

---

## Datasets

The project focuses on standard citation graph datasets commonly used in graph mining and graph neural network research, such as:

- Cora
- CiteSeer
- PubMed

In these datasets:

- nodes represent papers or documents
- edges represent citation relationships
- node features represent document attributes
- labels represent document categories

---

## Repository Contents

```text
graph-mining-node-classification/
├── assets/
│   └── poster.pdf
├── notebooks/
│   └── graph_mining_project.ipynb
├── .gitignore
└── README.md
```

Main files:

- [`notebooks/graph_mining_project.ipynb`](notebooks/graph_mining_project.ipynb) — main project notebook
- [`assets/poster.pdf`](assets/poster.pdf) — project poster

---

## Project Notebook

The main implementation and experiments are included in:

```text
notebooks/graph_mining_project.ipynb
```

The notebook contains the project workflow, including model setup, training, evaluation, and comparison.

To use the notebook, open it in Jupyter Notebook, JupyterLab, VS Code, or Google Colab and run the cells step by step.

---

## Project Poster

The project poster summarizes the motivation, method, experiments, and results.

Poster file:

```text
assets/poster.pdf
```

---

## Results Summary

The project compares GCN and GraphSAGE for node classification on citation graph datasets.

The results show that graph neural networks can use both node attributes and graph connectivity to improve node classification performance.

Performance varies depending on:

- dataset
- graph structure
- model choice
- training configuration
- neighborhood aggregation method

The detailed results and discussion are included in the notebook and poster.

---

## Topics Covered

This project covers:

- graph mining
- graph neural networks
- graph representation learning
- node classification
- citation network analysis
- GCN
- GraphSAGE
- semi-supervised learning on graphs

---

## Role in Portfolio

This project supports the AI/CS side of my portfolio.

It complements my other projects in embedded AI, dynamic systems, Kalman filtering, and sensor-based condition monitoring by showing experience with graph-based machine learning.

Together, these projects support a broader direction:

```text
AI / ML methods for structured, physical, and sensor-based systems
```

---

## Limitations

This repository is based on a university course project and is currently organized mainly around a notebook and poster.

Current limitations:

- code is notebook-based rather than a full Python package
- no separate training scripts are included yet
- no `requirements.txt` file is included yet
- exported result figures are not separated into a `results/` folder
- reproducibility depends on the notebook environment

These limitations are acceptable for a course project archive, but future improvements could make the repository more reproducible and project-like.

---

## Future Improvements

Possible next steps:

- add a `requirements.txt` file
- export key result figures into a `results/` folder
- convert notebook code into Python scripts
- add clearer experiment tables
- compare additional graph neural network models
- add a short explanation of dataset statistics
- improve reproducibility instructions

---

## Summary

This project demonstrates node classification using graph neural networks on citation graph data.

It provides experience with:

- graph-structured data
- graph neural network models
- node-level prediction
- GCN and GraphSAGE comparison
- AI/CS-oriented machine learning workflows

This makes it a useful portfolio project for showing graph mining and machine learning background alongside embedded AI and intelligent physical system projects.
