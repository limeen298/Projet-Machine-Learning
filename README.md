# Projet-Machine-Learning

For our machine learning course, we chose to develop a model capable of predicting whether a specific URL is Legitimate or Phishing based on its features.

## Structure

The project follows this structure:
1.  **Data Analysis (EDA):** Checking data quality, correlation matrix, and class balance.
2.  **Pre-processing:** Scaling data (StandardScaler) and splitting into Train/Test sets.
3.  **Dimensionality Reduction:** Using PCA for visualization.
4.  **Modeling:** Implementation of Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
5.  **Conclusion:** Comparing models based on Accuracy and Confusion Matrices.


## Results

* **Logistic Regression:** 95.2% Accuracy
* **Decision Tree Classifier:** 96.5% Accuracy 
* **Decision Tree with GridSearch:** 96.5% Accuracy
* **Random Forest:** 97.5% Accuracy
* **Gradient Boosting:** 97.9% Accuracy

## Conclusion:
The **Gradient Boosting Classifier** provided the best performance. It achieved the highest accuracy (97.9%) and demonstrated the best capability to reduce critical errors (False Negatives), making it the most suitable model for a cybersecurity context.