# DM-FAD: Federated Dual-Modal Anomaly Detection for Healthcare Insurance Fraud Analytics

# 1. Overview 
DM-FAD is a federated learning-based fraud detection system integrating structured and unstructured data modalities. It ensures privacy preservation by decentralizing model training while achieving high fraud detection accuracy.
# 2. System Components 
| Component           | Function              | Technology Used  |
| ------------------- |:---------------------|:---------------- |
| Structured Pipeline | Processes claims data | Autoencoder      |
| Text Pipeline       | Processes OCR documents |   BERT         |
| Fusion Layer    | Combines outputs           |    Weighted scoring  |
| Federated Layer    | Aggregates models           |    FedAvg  |
| Security Layer    | Ensures privacy           |    DP + Encryption  |

# 3. Requirements
| Library           | Purpose              | Version  |
| ------------------- |:---------------------|:---------------- |
| Numpy | Numerical operations | 1.24.4      |
| Pandas       | Data processing |   2.0.3         |
| scikit-learn    | ML models           |    1.3.0  |
| Matplotlib    | Visualization           |    3.7.2  |
| Torch    | Deep learning           |    latest  |
| Transformers    | BERT models           |    latest  |
| Pytesseract    | OCR           |    latest  |
| opencv-python    | Image processing           |    latest  |

# 4. requirements.txt
    numpy==1.24.4 
    pandas==2.0.3 
    scikit-learn==1.3.0 
    matplotlib==3.7.2 
    torch 
    transformers 
    pytesseract 
    opencv-python 

# 5. Folder Structure
    DM-FAD-PROJECT/ 
    ├── FRAUD_ANALYTICS.ipynb 
    ├── requirements.txt 
    ├── README.md 
    ├── DATA/ 
    │   ├── claims.csv 
    │   └── documents/ 
    └── outputs/ 

# 6. Execution Steps
    ## 6.1. Install dependencies
    ## 6.2. Place dataset
    ## 6.3. Run Jupyter
    ## 6.4. Execute notebook

# 7. Outputs
| Output           | Description              |
| ------------------- |:---------------------|
| Fraud Score | Probability of fraud | 
| Anomaly Score       | Reconstruction error | 
| Embeddings    | Text semantic vectors           | 
| Graphs    | Loss visualization           |


