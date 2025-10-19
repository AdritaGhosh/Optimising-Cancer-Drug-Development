# Optimising Cancer Drug Development using Machine Learning
This project applies Machine Learning (ML) to enhance cancer drug discovery by predicting adverse drug events during early development. Through QSAR modelling, ensemble learning, and transfer learning, it builds a robust safety model capable of identifying safe, effective lead compounds and reducing drug attrition rates.
## Design of New Ideas and Approach
A new ML-QSAR hybrid framework is proposed, combining molecular descriptors from SMILES data, ensemble learning, and transfer learning for robust safety and efficacy prediction.
Key steps include:
* Generating domain-specific features (PAE, Class, Adverse Event)
* Dataset segmentation (Antagonist and Viability subsets)
* Model training (Random Forest, XGBoost, MLP)
* Ensemble stacking and transfer learning for generalization
Ethical and legal compliance (GDPR, HIPAA) is emphasized along with commercial scalability and reliability.
## Implementation
Process pipeline:
* Data Preprocessing – cleaning, encoding, and scaling features
* Feature Engineering – creating and encoding molecular descriptors and safety markers
* Model Development – training classification/regression models with cross-validation
* Ensemble and Deep Neural Network (DNN) – stacking best models into a unified safety predictor
* Transfer Learning – adapting the pre-trained model to new Viability datasets
Despite technical challenges (e.g., data imbalance, computational load), optimized solutions achieved highly accurate and reproducible results.
## Evaluation
Evaluation focuses on model performance:
* Ensemble learning achieved 99.69% accuracy.
* Transfer learning achieved 99.90% accuracy.
* AUC = 0.99, confirming strong predictive capability.
The top lead compounds identified include Oxymetholone and Azoxystrobin, both showing high efficacy and no adverse effects.
Minor limitations include class imbalance (difficulty recognizing rare adverse events) and potential overfitting in regression models.
## Conclusions and Future Work
