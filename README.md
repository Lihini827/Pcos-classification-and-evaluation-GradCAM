# Pcos-classification-and-evaluation-GradCAM
Identification of Polycystic Ovarian Syndrome using ultrasound images in Integration with transfer learning models, Data Augmentation and evaluate model using Explainable AI model GradCAM 

1. NansnetConGrad.ipynb
.Transfer learning model using NASNetMobile.
.A Conv1D layer was added to enable Grad-CAM visualization.
.Includes 5-fold Stratified Cross-Validation.
.Generates a classification report.

2. Efficientnetb0pcos.ipynb
.Transfer learning model using EfficientNetB0.
.A Conv2D layer was added to implement Grad-CAM visualization.
.Includes 5-fold Stratified Cross-Validation.

3. pcosALL.ipynb
Visualizations include:
.Classification report
.Confusion matrix
.ROC curve
.Loss and accuracy curves

4. XAIpcos.ipynb
.Generates Grad-CAM visualizations.
.To generate Grad-CAM for a specific class:
.If targeting the Normal class, make sure "Normal" is the first label in the class list.
.If targeting the PCOS class, place "PCOS" first in the class label list.

5. ntry2impPcosSHAPtry.ipynb
.A small effort to implement SHAP visualizations for both PCOS and Normal classes.





