Penguin Species Classification using Machine Learning
Overview
This project demonstrates a machine learning approach to classifying penguin species based on their physical characteristics. Using the Palmer Penguins dataset, we explore data preprocessing, visualization, model training, and evaluation to build an accurate classification model.

Dataset
The dataset contains the following features:

CulmenLength: Length of the penguin's bill (mm)
CulmenDepth: Depth of the penguin's bill (mm)
FlipperLength: Length of the flipper (mm)
BodyMass: Body mass in grams
Species: Target variable (Adelie, Gentoo, Chinstrap)
Steps and Methodology
1. Data Preparation
Loaded the dataset and displayed a random sample.
Checked and handled missing values.
Visualized feature distributions using box plots to understand species differences.
2. Model Training
Used Logistic Regression as the initial classification model.
Split the dataset into training (70%) and testing (30%) sets while maintaining class distribution using stratification.
3. Model Evaluation
Calculated accuracy, precision, and recall.
Visualized results using a confusion matrix and ROC curves.
4. Model Improvement
Implemented data preprocessing using a pipeline (scaling numeric features).
Switched to a Support Vector Machine (SVM) for comparison.
Evaluated the SVM model with updated performance metrics.
5. Model Deployment
Saved the trained model using joblib.
Demonstrated model inference with new sample data.
Results
The SVM model achieved 98% accuracy, with an AUC score of 0.999, indicating excellent classification performance.
Technologies Used
Python (pandas, numpy, matplotlib, scikit-learn)
Machine Learning Algorithms (Logistic Regression, SVM)
Data Visualization (Matplotlib, Boxplots, Confusion Matrix, ROC Curves)

Conclusion
This project successfully classifies penguin species using machine learning. By leveraging feature engineering, model tuning, and pipeline preprocessing, we built a good classifier with high accuracy.
