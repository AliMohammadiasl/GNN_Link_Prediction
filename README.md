# GNN Link Prediction for Social Learning Networks


This repository contains ongoing research on using Graph Neural Networks (GNNs) for link prediction in Social Learning Networks (SLNs). The project aims to predict future interactions between students in a classroom setting, based on communication history and network features. 

### Overview
The goal of this project is to train a GNN-based model to predict future links (interactions) between nodes (students) in a social network. The research uses multiple SLN datasets, comparing individual and combined dataset performance using metrics like AUC and accuracy.

### Methodology
**Data:** SLN datasets representing classroom communication.

**Graph Construction:** Nodes represent students, edges represent communication links.

**Model:** GNNs are used to learn node embeddings and predict future links.

**Evaluation:** The model is evaluated on AUC and accuracy, with a focus on cross-classroom performance.

### Libraries Used
**DGL (Deep Graph Library):** For building and training graph neural networks.

**NetworkX:** For constructing and manipulating the graph data structures.

**PyTorch:** For deep learning model development and training.

**NumPy:** For numerical operations and handling arrays.

**Pandas:** For data manipulation and analysis.

**Scikit-learn:** For computing metrics such as AUC and accuracy.


### Results (In Progress)
Initial results show promising link prediction accuracy across datasets. Detailed results will be provided upon completion.

Contact
For any questions, feel free to reach out:

Email: amohammadiasl@ucsd.edu