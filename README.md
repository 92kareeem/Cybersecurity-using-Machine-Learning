# Cybersecurity Threat Classification Using Machine Learning

## Overview
This project focuses on detecting network intrusions using machine learning techniques. It involves preprocessing a cybersecurity dataset, feature selection, model training, evaluation, and visualization.

## Dataset
The dataset used in this project is a cybersecurity network intrusion detection dataset that contains various network traffic features labeled as normal or malicious traffic.

### Download the Dataset
1. **Option 1: Provided CSV File**
   - The dataset (`Train_data.csv`) is included in this repository.

2. **Option 2: Download from External Source**
   - If you need a similar dataset, you can download publicly available intrusion detection datasets such as NSL-KDD, CIC-IDS2017, or UNSW-NB15 from:
     - [NSL-KDD Dataset](https://www.unb.ca/cic/datasets/nsl.html)
     - [CIC-IDS2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)
     - [UNSW-NB15 Dataset](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)
   - After downloading, place the dataset CSV file in the project directory.

## Installation
Before running the code, ensure you have the required dependencies installed.

### Install Dependencies
```bash
pip install -r requirements.txt
```

## Running the Code
Follow these steps to execute the project:

1. **Load and Preprocess Data**
   - Run the notebook or Python script that loads the dataset, cleans missing values, and normalizes the data.

2. **Feature Selection**
   - The script applies correlation-based feature selection to remove highly correlated features.

3. **Model Training**
   - Three models are trained: Random Forest, SVM, and Neural Network.

4. **Model Evaluation**
   - The models are evaluated based on accuracy, precision, recall, F1-score, and ROC-AUC.

5. **Visualization**
   - Various plots, such as feature importance and confusion matrices, are generated.

### Running the Jupyter Notebook
```bash
jupyter notebook CyberThreat.ipynb
```

## Results
### Model Comparison
| Model           | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|----------------|----------|-----------|--------|----------|---------|
| Random Forest  | 1.00     | 1.00      | 1.00   | 1.00     | 0.9998  |
| SVM            | 0.98     | 0.98      | 0.98   | 0.98     | 0.9976  |
| Neural Network | 0.99     | 0.99      | 0.99   | 0.99     | 0.9991  |

## Acknowledgments
This project is inspired by various cybersecurity datasets and intrusion detection methodologies. Special thanks to open-source datasets and tools used in this project.

## License
This project is licensed under the MIT License.

