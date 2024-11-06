# Machine-Learning-Methodologies-in-Finance

## Overview

This project aims to compare various machine learning methodologies across three distinct datasets in the finance domain. By evaluating these methods, we seek to derive insights into their performance and applicability in real-world scenarios, particularly within banking and financial services.

## Datasets

1. **Portuguese Bank Marketing Dataset**
   - **Description:** Contains information on direct marketing campaigns (via phone calls) conducted by a Portuguese bank.
   - **Objective:** Predict whether a client will subscribe to a term deposit based on their financial profile and marketing interactions.

2. **Bank Turnover Dataset**
   - **Description:** Includes customer characteristics and tenure data to analyze customer retention.
   - **Objective:** Create a classifier to predict if a bank client will leave in the next six months.

3. **ANZ Banking Dataset**
   - **Description:** Contains transaction data for 100 customers over a 92-day period.
   - **Objective:** Use financial data to predict a bank customer's income.

## Methodologies

The project implements various machine learning methodologies, including:

- **Classification Techniques:** 
  - Linear Regression
  - Decision Trees
  - Random Forest
  - K-Nearest Neighbors (KNN)
  
- **Evaluation Metrics:**
  - R-Squared (R²)
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Confusion Matrix
  - F1 Score

These techniques and metrics are applied using the Knowledge Discovery in Databases (KDD) methodology to ensure a comprehensive data analysis workflow.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** 
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Development Environment:** Jupyter Notebook

## Results

- The Random Forest Classifier achieved an accuracy of **92.16%** for the Portuguese Bank Marketing dataset.
- The Bank Turnover dataset analysis resulted in varied F1 scores for different models, highlighting the impact of data imbalance.
- Regression techniques were applied to the ANZ Banking dataset to predict salaries, with R² values indicating the fit of the model.

## Conclusion

The findings demonstrate that different machine learning methodologies can significantly impact the predictive capabilities within financial contexts. The project emphasizes the importance of choosing the right algorithm and evaluation metrics to address specific financial questions.

## Future Work

Future enhancements could include:
- Exploring additional machine learning models for deeper insights.
- Implementing more robust data preprocessing techniques to handle imbalances and improve model accuracy.
- Expanding the analysis to include real-time data processing for financial applications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
