# Fetal_Health_Multi-Class_Classification
Here deep learning approach is used to classify fetal health to three discreet classes 'Normal', 'Suspect' and 'Pathological'.
Model summary:
Layer (type)                 Output Shape              Param #   
=================================================================
dense_5 (Dense)              (None, 8)                 72        
_________________________________________________________________
dense_6 (Dense)              (None, 10)                90        
_________________________________________________________________
dense_7 (Dense)              (None, 3)                 33        
=================================================================
Total params: 195
Trainable params: 195
Non-trainable params: 0

Steps:
EDA
Missing value check
Outlier check
Feature scaling using robust scaler
Multicollinearity check using correlation plot
Mutual information classifier for dimensionality reduction
Model building
Evaluation
Explaining results using shap and lime methods.
