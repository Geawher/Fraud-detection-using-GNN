# Fraud-detection-using-GNN
This project utilizes Graph Neural Networks (GNNs) to develop an advanced fraud detection system. By leveraging the power of GNNs, the project aims to accurately identify fraudulent activities by modeling the intricate relationships and dependencies among entities involved in fraudulent behavior.

Two methods were used : 

* Create a multigraph graph with [NetwokX](https://networkx.org/) and a GNN model with [PyToch](https://pytorch.org/)
* Use inductiveGRL library : In this part we will base our work on the paper [Inductive Graph Representation Learning for fraud detection](https://www.sciencedirect.com/science/article/abs/pii/S0957417421017449) written by RafaëlVan Belle, Charles Van Damme, Hendrik Tytgat and JochenDe Weerdt.

Charles has created a python library with the name of inductiveGRL for the experimental setup of their paper.
  
IBM dataset : 

* [Link1](https://github.com/IBM/TabFormer) GitHub
* [Link2](https://ibm.ent.box.com/v/tabformer-data) IBM@Box
*  [Link3](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions) Kaggle
