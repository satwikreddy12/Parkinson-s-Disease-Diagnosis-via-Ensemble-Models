# Parkinson-s-Disease-Diagnosis-via-Ensemble-Models
This project focuses on diagnosing Parkinson’s Disease (PD) using machine learning, particularly through ensemble models.

Parkinson’s Disease is a neurological disorder marked by symptoms like tremors, stiffness, and impaired speech. Given the characteristic vocal features exhibited by PD patients, this project uses voice recordings to aid in early and non-invasive diagnosis. By applying various machine learning algorithms to voice data, this project aims to develop an effective screening tool for Parkinson's.

### Dataset<br/>
The dataset contains vocal recordings with attributes such as:<br/>

Fundamental Frequency Measures (MDVP: Fo, MDVP: Flo, etc.)<br/>
Frequency and Amplitude Variation (Jitter, Shimmer)<br/>
Noise Ratios (NHR, HNR)<br/>

### Models Used<br/>
The project applies the following machine learning models:<br/>

Random Forest: Used to create an ensemble classifier for predicting Parkinson's.<br/>
AdaBoost: Boosting model that combines weak classifiers for improved accuracy.<br/>
Stacked Ensemble Model: Combines multiple model predictions to improve the final accuracy.<br/>
The models are evaluated with metrics like confusion matrix and classification reports for accuracy.<br/>

### Approach<br/>
Data Preprocessing: The data is scaled and processed to be compatible with the machine learning models.<br/>
Model Training: Multiple ensemble models are trained to classify vocal recordings.<br/>
Evaluation: Accuracy metrics and feature importance are analyzed for model insights.<br/>

![image](https://github.com/user-attachments/assets/987967f4-1cd3-4e40-830a-d0c2bfc9fc3a)<br/>

### Key Code Elements<br/>
Feature Importance Analysis using Random Forest.<br/>
Stacking and Boosting techniques to create meta-models.<br/>
Model Evaluation using classification metrics to determine the model's efficacy.<br/>

![image](https://github.com/user-attachments/assets/af1ab80c-b3db-4131-9b6e-24a89eafcc69)<br/>


### Conclusion
This project demonstrates the use of ensemble techniques in diagnosing Parkinson’s Disease. The developed models aim to provide a non-invasive diagnostic tool, enhancing early detection accuracy.
![image](https://github.com/user-attachments/assets/8f3258ae-8d2c-4fb5-9140-0a6802ad009c)

