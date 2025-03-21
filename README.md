# Inductive-GNN-Wind
# InductiveWindGNN

InductiveWindGNN is a Graph Neural Network (GNN) model designed for wind speed prediction using an inductive learning approach. The model constructs graphs using K-Nearest Neighbors (KNN) and utilizes IGNNK with GRU to predict wind speed in a complete new node introduced in the graph structure using the spatial relation and temporal changes.

## Features
- **KNN-based graph construction** using spatial coordinates (latitude & longitude)
- **Inductive learning** to predict wind speed for unseen stations
- **GCN layers** to capture spatial relationships
- **GRU integration** for temporal dependencies
- **Evaluation metrics:** MAE, RMSE, and R² Score

## Installation
```bash
git clone https://github.com/ManojDatla5657/Inductive-GNN-Wind.git
cd Inductive-GNN-Wind
pip install -r requirements.txt
