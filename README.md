Integration of Machine Learning and Explainable AI (XAI) approaches for Optimizing Battery Health on Electric Vehicles


This project explores using machine learning (ML) to predict electric vehicle (EV) battery health. Its primary goal is to address the "black box" nature of complex ML models by integrating Explainable AI (XAI) techniques. The project aims to not only classify battery health with high accuracy but also to provide transparent, human-understandable explanations for the model's predictions.

Key Features 🧠
Battery Health Classification: Develops and validates ensemble ML models for accurately classifying the state of health (SOH) of EV batteries.

Model Explainability (XAI): Utilizes the SHapley Additive exPlanations (SHAP) framework to interpret model predictions. This provides insights into which features are most important for battery health classification.

Feature Importance Analysis: Employs SHAP to identify and rank the key features that drive battery degradation, enhancing understanding of the underlying physical processes.

Performance Validation: The proposed system is verified using a publicly available EV battery dataset from Kaggle.

Methodology ⚙️
The project follows a systematic workflow to achieve its objectives:

Data Collection and Preprocessing: An EV battery dataset with approximately 100,000 records is used. The data is preprocessed to handle missing values using imputation, followed by a train-test split (80/20).

Model Training: Three high-performance ensemble classifiers—XGBoost, CatBoost, and ExtraTreesClassifier—are trained on the preprocessed data.

Performance Evaluation: Models are evaluated using a confusion matrix to calculate metrics such as Accuracy, Precision, Recall, and F1-score.

XAI Application: The trained models are integrated with the SHAP library to compute SHAP values, providing both local (instance-level) and global (overall feature importance) explanations.

Analysis: The project concludes by analyzing the model performance metrics alongside the SHAP explanations to demonstrate how XAI enhances understanding of the predictive outcomes.

Project Report Structure 📄
This repository contains the work for the project report, which is structured as follows:

Chapter 1: Introduction: Provides background on EVs and battery health, and defines the problem statement.

Chapter 2: Objective: Details the specific goals of the project.

Chapter 3: System Requirements: Outlines the hardware and software specifications used.

Chapter 4: Literature Survey: Reviews related research and existing work.

Chapter 5: Methodology: Describes the detailed steps of data processing, modeling, and XAI application.

Chapter 6: Implementation: Discusses the tools and libraries used to execute the methodology.

Chapter 7: Performance Analysis: Presents and evaluates the results of the trained models.

Chapter 8: Conclusion: Summarizes the key findings and contributions of the project.

Chapter 9: Future Enhancement: Suggests potential future work and improvements.

Author 🧑‍🎓
Name: PAKTHAPRIYAN S

Registration Number: 225058031

Supervised by: Dr. R. BALA KRISHNAN
