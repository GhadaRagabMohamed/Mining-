# San Francisco Crime Analysis and Classification Project

## Overview
This project aims to analyze crime data from San Francisco and build a machine learning model to classify crime categories based on features such as location, time, and crime description.

---

## Requirements
- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - pyclustering

---

## Usage Instructions

1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn pyclustering

2. Download the train.csv.zip dataset and place it in the project directory or update the file path in the script.


3. Run the script step-by-step to perform data analysis, cleaning, clustering, and model training.




---

Project Steps

Loaded and performed initial exploratory data analysis.

Cleaned data by removing outliers using the IQR method.

Applied k-Medoids clustering on geographical coordinates.

Extracted and encoded temporal and textual features.

Trained a Random Forest classifier to predict crime categories.

Evaluated the model and visualized results using a confusion matrix.



---

Results

The model achieved approximately 80% accuracy in classifying crime categories, with optimized parameters for improved performance and reduced complexity.
