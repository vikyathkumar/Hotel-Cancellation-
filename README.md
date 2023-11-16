This project aims to address the challenge of hotel booking cancellations by leveraging predictive modeling. Hotel cancellations can significantly impact revenue, and to avoid implementing cost-cutting measures, predicting cancellations becomes crucial. The goal is to use machine learning to identify patterns from past bookings and predict the cancellation probability of future bookings.

## Key Steps and Highlights

- **Data Exploration:** Conducted detailed exploration of features using boxplots and distributions, identifying data imbalances, and outliers.
  
- **Data Preprocessing:** Addressed null values using various methods, including forward fill for categorical features, mean fill for numerical values, and dropped rows with a null percentage of 0.005.

- **Feature Engineering:** Created a correlation matrix to identify and drop unnecessary features. Used label encoding over one-hot encoding to reduce the size of the resultant dataset.

- **Model Selection:** Chose Logistic Regression and Decision Trees for predicting the target variable, focusing on accuracy for model performance. Resolved overfitting using Ensemble techniques like Random Forest.

- **Model Evaluation:** Utilized confusion matrix to calculate recall, ensuring a comprehensive assessment of model performance.

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Logistic Regression, Decision Trees, Random Forest

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Hotel-Cancellation-Prediction.git
   cd Hotel-Cancellation-Prediction

   pip install -r requirements.txt

   jupyter notebook
Remember to replace the placeholder URLs and customize the content based on your actual project structure and information.

