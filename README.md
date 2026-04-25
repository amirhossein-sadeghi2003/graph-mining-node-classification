Graph Mining Node Classification

This repository contains a graph mining course project focused on node classification using graph neural networks.

Description

The project studies node classification on citation graph datasets and compares two graph neural network models:

GCN
GraphSAGE

The work is based on standard graph datasets commonly used in graph mining and geometric deep learning.

Main Idea

In citation networks, nodes represent documents and edges represent citation relations between them.

The goal is to predict the class or category of each node by using:

node features
graph structure
neighborhood information

This project explores how graph neural networks can use both feature information and graph connectivity for node classification.

Models

The project compares the following models:

GCN (Graph Convolutional Network)
GraphSAGE

These models are widely used in graph representation learning and node classification tasks.

Datasets

The project uses well-known citation graph datasets such as:

Cora
CiteSeer
PubMed

These datasets are common benchmarks in graph mining and graph neural network research.

Repository Contents

This repository includes:

the main project notebook
the project poster

Main files:

notebooks/graph_mining_project.ipynb
assets/poster.pdf
Results

The project compares model behavior and performance on citation graph datasets and summarizes the main findings in the notebook and poster.

Based on the project presentation, both GCN and GraphSAGE achieve strong results, with some variation across datasets and training settings.

How to Use

Open the notebook file and run the cells step by step:

notebooks/graph_mining_project.ipynb

You can also view the poster file here:

assets/poster.pdf

Topics Covered

This project is related to:

graph mining
graph neural networks
node classification
citation networks
machine learning on graphs
Notes

This repository is a cleaned and simplified version of a university course project, prepared for portfolio and GitHub presentation.

Future Improvements

Possible next steps:

convert the notebook into a cleaner project structure
add a requirements file for reproducibility
add exported result figures
compare more graph learning models
improve the documentation of training and evaluation details
