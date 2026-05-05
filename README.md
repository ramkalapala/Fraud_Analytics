# DM-FAD: Federated Dual-Modal Anomaly Detection for Healthcare Insurance Fraud Analytics

# 1. Overview 
DM-FAD is a federated learning-based fraud detection system integrating structured and unstructured data modalities. It ensures privacy preservation by decentralizing model training while achieving high fraud detection accuracy.
# 2. System Components 
| Component           | Function              | Technology Used  |
| ------------------- |:---------------------|:---------------- |
| Structured Pipeline | Processes claims data | Autoencoder      |
| Text Pipeline       | Processes OCR documents |   BERT         |
| Fusion Layer    | Combines outputs           |    Weighted scoring  |
