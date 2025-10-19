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
   High-quality cancer compound datasets (Antagonist & Viability)
   Molecular descriptors generated via RDKit
* Feature Engineering
- Novel attributes: PAE (Potential Adverse Event), ADVERSE EVENT, Lipinski’s RO5 compliance
* Model Development
- ML methods: Random Forest, Gradient Boosting, XGBoost, Neural Networks
- Ensemble stacking & DNN integration
* Transfer Learning
- Adaptation to new datasets for enhanced model generalization
* Evaluation
- Metrics: Accuracy, F1-score, Precision, Recall, ROC-AUC
