# K-Nearest Neighbor (KNN) and Decision Tree (DT) Classification algorithms for Detecting Diabetes

**DESCRIPTION**

Applying and analyzing the performance of two Machine Learning (ML) classification algorithms - K-Nearest Neighbor (KNN) and Decision Tree (DT) algorithms - in predicting likelihood of diabetes from a dataset containing 9 parameters (8 features, and 1 target variable) for a total of for 770 people. 

**OBJECTIVE**

To develop and compare ML classification models (DT and KNN) that predict the likelihood of diabetes based on patient health data.

**STRUCTURE**

The repository includes the .ipynb file, .csv file (Dataset), and README.md file.

**DATASET**

- The dataset used is a .csv file, created by Prit Sheta and sourced from Kaggle. It contains health data for 770 individuals. It includes 8 features — Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, and Age — used to predict    the target variable Outcome (Diabetic or Not).
- Features such as Glucose, BloodPressure, SkinThickness, Insulin, and BMI contained unrealistic zero values representing missing data. These were replaced with the median of the respective feature's distribution.
- Since KNN model is sensitive to feature scales, normalization was applied to scale all features to a [0,1] range, ensuring balanced distance calculations.

**TOOLS & LIBRARIES**

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- sklearn
- .csv reading
- Data preprocessing

**EVALUATION METRICS**

- Heatmap
- Gini index
- Precision
- Recall
- F1-Score
- Confusion matrix
- Accuracy
- Sensitivity
- Specificity
- ROC Curve

**RESULTS**

| Model | Accuracy | Precision |
| ----- | -------- | --------- |  
|  KNN  |   71%    |    76%    |
|  DT   |   67%    |    72%    |

The KNN model showed greater Accuracy and Precision in predicting Diabetes, compared to the DT model.

**HOW TO RUN**

1. Clone the repository or download the .ipynb file.
2. Open the notebook in Google Colab or Jupyter.
3. Run the cells sequentially.
4. Dataset is typically included using pandas or must be uploaded manually when prompted.

**ACKNOWLEDGMENTS**

- Kaggle community
- Scikit-learn documentation

**CONTACT**

Feel free to reach out: viveikcs@gmail.com
