# Breast-Cancer-Classification
Breast Cancer Classification Using Ensemble Hard Voting with Random Under-Sampling. A classification technique to expedite the diagnostic process by identifying whether the tumor is benign or malignant.

The ensemble learning-based Hard Voting (HV) technique has been combined with random under-sampling using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. This dataset provides several features upon performing Fine Needle Aspirate (FNA) test to each affected individual, and five features have been chosen to accomplish the classification task. These features have been further scaled using RobustScaler, and the classes (benign or malignant) were balanced using random under- sampling to achieve an accurate outcome. Four distinguished ML classifiers, e.g., Decision Tree Classifier (DTC), k-Nearest Neighbor (KNN), Random Forest (RF), and Support Vector Machine (SVM), have been applied to form an HV meta-classifier. The HV meta-classifier has obtained 99.42% test accuracy in classifying breast cancer incidents. This result has been further verified by considering other distinct parameters.
