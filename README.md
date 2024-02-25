# Weather_Prediction_ML_Project
 
## Project Overview: Analyzing Seattle's Rainfall

### Goal:
- Examine rain frequency, actual rainfall, seasonal trends, and predictability in Seattle using data from 1948 to 2017.

### Data Source:
- Dataset obtained from [Kaggle](https://www.kaggle.com/rtatman/did-it-rain-in-seattle-19482017).

### Summary of Findings:
- Seattle experiences frequent rainfall compared to the national average, but ranks mid-range in actual precipitation.
- Summers are typically dry and warm, while winters exhibit less variability in temperature.
- Modeling suggests one-day lag precipitation and temperature are significant predictors of rain.

### Tools Used:
- Libraries: numpy, pandas, collections, random, matplotlib, sklearn, seaborn, tabulate.

### Concepts Used:
- The machine learning models used in this code for prediction are:

1. **Random Forest Classifier:** Utilized for binary classification to predict whether it will rain on a given day in Seattle based on historical weather data.

2. **Logistic Regression:** A logistic regression is commonly used for binary classification tasks, similar to the random forest classifier.

3. **Support Vector Classifier (SVC):** SVC is another option for binary classification tasks. It works by finding the hyperplane that best separates the classes in the feature space.

- These models are trained and evaluated using techniques such as cross-validation, grid search for hyperparameter tuning, and performance evaluation metrics like accuracy, precision, recall, F1 score, and area under the ROC curve (AUC).

### Files:
- Dataset: [seattleWeather_1948-2017.csv]
- Prediction Notebook: [Weather_Prediction.ipynb]
- Supplementary Image: [national_rainfall.png]
- Repository Overview: [README.md]

### Acknowledgements:
- Data: Kaggle
- Support: Stack Overflow