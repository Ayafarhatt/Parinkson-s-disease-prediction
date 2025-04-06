# Parkinson's Disease Prediction

This project aims to predict the presence of Parkinson's disease using machine learning techniques.

## Dataset

The project utilizes the "Parkinsons.data" dataset, which contains various speech and voice measurements from individuals with and without Parkinson's disease.

## Methodology

1. **Data Loading and Exploration:**
   - The dataset is loaded using Pandas.
   - Exploratory data analysis is performed to understand the data's structure and characteristics.

2. **Data Preprocessing:**
   - Missing values are handled (if any).
   - The dataset is split into training and testing sets.

3. **Model Training and Evaluation:**
   - **Logistic Regression:** A logistic regression model is trained on the data and evaluated using metrics like accuracy, classification report, and confusion matrix.
   - **SMOTE for Class Imbalance:** The Synthetic Minority Over-sampling Technique (SMOTE) is used to address class imbalance in the dataset. The model is retrained and reevaluated.
   - **Data Scaling:** Standard scaling is applied to the data to improve model performance. The logistic regression model is retrained and reevaluated.
   - **Support Vector Machine (SVM):** A Support Vector Classifier with a linear kernel is trained on the data and evaluated for its performance. A confusion matrix is generated and visualized using a heatmap.

## Results

The performance of the models is assessed based on the chosen evaluation metrics. The best-performing model and its results are highlighted.

## Conclusion

The project demonstrates the application of machine learning in predicting Parkinson's disease. The results provide insights into the effectiveness of different models and techniques for this task.

## Dependencies

- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Run the Jupyter notebook to execute the code.

## Contributing

Contributions to the project are welcome! Please feel free to submit pull requests for bug fixes, enhancements, or new features.


