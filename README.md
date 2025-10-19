# Optimising Cancer Drug Development using Machine Learning
This repository hosts the implementation and documentation for a research project exploring machine learning-based prediction of adverse events in cancer drug discovery.
The project integrates QSAR modeling, ensemble learning, and transfer learning to identify safe and effective lead compounds early in the development process, reducing costs and improving patient outcomes.
## Overview
Traditional cancer drug discovery is slow, expensive, and has a low success rate (~6%).
This project applies Machine Learning (ML) to accelerate early-stage research by predicting potential adverse events (AEs) in candidate molecules before clinical testing.
The model integrates Quantitative Structure-Activity Relationship (QSAR) features, large molecular datasets, and state-of-the-art ML techniques (Random Forest, XGBoost, Deep Neural Networks) to produce reliable toxicity and efficacy predictions.
## Features
* Automated feature generation using SMILES molecular notation
* QSAR-based drug activity and safety prediction
* Advanced ensemble learning combining multiple model architectures
* Transfer learning for cross-dataset generalisation
## Methodology
* Data Acquisition & Preprocessing
  - High-quality cancer compound datasets (Antagonist & Viability)
  - Molecular descriptors generated via RDKit
* Feature Engineering
  - Novel attributes: PAE (Potential Adverse Event), ADVERSE EVENT, Lipinski’s RO5 compliance
* Model Development
  - ML methods: Random Forest, Gradient Boosting, XGBoost, Neural Networks
  - Ensemble stacking & DNN integration
* Transfer Learning
  - Adaptation to new datasets for enhanced model generalization
* Evaluation
  - Metrics: Accuracy, F1-score, Precision, Recall, ROC-AUC
## Model Evaluation
* Accuracy: up to 99.9%
* Precision/Recall: 0.97–1.00
* AUC: ≈ 1.00
* Leads Identified: Oxymetholone (Antagonist) and Azoxystrobin (Viability datasets)
## Results
* Enhanced early detection of adverse events
* Reduced model bias using ensemble and transfer learning
* Scalable, reproducible prediction workflow
* Framework adaptable to broader therapeutic areas
## Technologies Used
* Python (Pandas, NumPy, RDKit, scikit-learn, TensorFlow, XGBoost)
* Jupyter Notebook
* Matplotlib / Seaborn for data visualization
## Dataset Description
This project uses publicly accessible datasets from open biomedical repositories to train and validate the machine learning safety model for predicting adverse drug events in cancer compounds. The datasets were selected for their reliability, data diversity, and compatibility with QSAR and High-Throughput Screening (HTS) modelling.
### Primary Dataset – Tox21 Aromatase Subset
The main dataset used in this project is the Tox21 Aromatase dataset obtained from the NIH Tox21 public database (a collaboration between the U.S. NIH, EPA, and FDA).
It includes chemical compounds tested for endocrine-disrupting (Aromatase inhibition) activity, providing features like:
* SMILES molecular structure strings
* Assay and channel outcomes
* Compound purity ratings and efficacy metrics
* Pharmacokinetic and concentration-response data
### Download source:
[Tox21 Data at NIH](https://tripod.nih.gov/tox21/pubdata/)
License: Public domain (U.S. Federal data; unrestricted academic use)
### Dataset Usage
All datasets were:
* Processed into RDKit-compatible SMILES format.
* Cleaned for missing, duplicate, and inconsistent values.
* Segmented into Antagonist and Viability subsets for efficacy and safety modelling.
* Scaled and label-encoded for use in ensemble learning pipelines.

## License
This is my MSc Data Science dissertation project completed at Nottingham Trent University (NTU) in 2024. The research, models, and code are made available solely for academic, educational, and non-commercial research purposes.
For inquiries or collaboration requests, please contact via the repository’s issue tracker or email listed in the project documentation.

