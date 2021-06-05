# Modelling Drug-Drug Interaction Prediction using Graph Neural Networks

This Repository contains the code used for a project as part of Deep Learning Course - Spring 2021

The idea here is to predict if an edge exists between two drugs. It can be used to predict if side-effects occur because of taking two or more drugs at once during medication

We used a method that was built on top of the [DECAGON](https://github.com/mims-harvard/decagon) model to predict drug-drug interactions:
1. By extracting the network structure features from DDI, DPI, PPI networks with graph neural networks (GNN)
2. Then a decoder takes a pair of nodes and predicts the type of edge between them
