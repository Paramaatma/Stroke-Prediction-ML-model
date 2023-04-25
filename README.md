# Stroke-Prediction-ML-model
Overview:
This project is aimed at building a machine learning model to predict the likelihood of a person having a stroke based on certain risk factors. The model uses a dataset of patient records including demographic information, lifestyle habits, and medical history to predict the probability of having a stroke.

Dataset:
The dataset used for this project is sourced from `*healthcare-dataset-stroke-data.csv Realtime health care dataset*` and contains records of 5110 patients with 12 attributes including age, gender, hypertension, heart disease, smoking status, etc. The data has been preprocessed and cleaned to remove any missing values or outliers.

Model Building
The model is built using Python and the Scikit-learn library. The dataset is split into training and testing sets with a ratio of 80:20. The model is trained using several algorithms including Logistic Regression, Decision Tree, Random Forest, Decision Tree and SVM, . The best performing algorithm is chosen based on accuracy, precision, recall, and F1 score.

Model Evaluation:
The model is evaluated using several performance metrics including accuracy, precision, recall, and F1 score. The results are compared with the baseline model and the best performing algorithm is chosen. The model is then fine-tuned using hyperparameter optimization to improve its performance.

Conclusion:
This project demonstrates the use of machine learning algorithms in predicting the likelihood of a person having a stroke based on their demographic and medical information. The model can be used by healthcare professionals to identify high-risk patients and take preventive measures to reduce the incidence of strokes.
