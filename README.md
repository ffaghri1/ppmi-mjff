# Classification and Prediction of Peri-Diagnostic Prognoses in Parkinson’s Patients using Machine Learning on Multi-modal Clinical

Faraz Faghri | Sep 07, 2016 

### Data:
The Parkinson's Progression Markers Initiative (PPMI) dataset

### Goal: 
1. At baseline, determine what are factors that predict clinical progression?
2. What are the sub-types of Parkinson’s disease based on clinical, molecular and imaging data?

### Summary of results:
1. We have identified 3 PD progression sub-types: low, mid, and high which progress at varying rates and also differ at baseline compared to healthy aging
2. We predict PD progression from baseline with 80-98% accuracy by PD subtype
3. We have identified statistically significant elements at baseline which predicts progression: MoCA delayed recall, UPDR3 rigidity, Sleep movement, etc.
4. We have improved the predictions of progression significantly by incorporating various machine learning, approaches as PD is such a heterogenous disease

### Description of Methods Used:
1. We used Gaussian Mixture Models as unsupervised machine learning for identifying PD prognosis subtypes differing at baseline and how they progress
2. Logistic regression as supervised classifier for predicting subtypes and their clinical progression from baseline
3. Randomized decision trees (a.k.a. extra-trees) for identifying important factors at baseline in prediction of clinical progression



