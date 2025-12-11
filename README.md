# Customer Churn Prediction with Feature Engineering 🚀

Predicting customer churn is a critical task for telecommunications companies aiming to reduce attrition and improve customer retention. This project demonstrates the impact of feature engineering and explores feature selection to build predictive models that accurately identify churn.

## 📌 Project Objective

The goal of this project is to:

- Build a baseline model using raw features.

- Engineer new features to enhance predictive performance.

- Apply feature selection to identify the most relevant features.

- Compare model performance and analyze the impact of feature engineering and selection.

## 🛠 Core Concepts Covered

Importance of Feature Engineering

- Creating meaningful features can significantly improve model performance.

Advanced Data Cleaning

- Handling missing values, inconsistencies, and data transformations.

Feature Creation Techniques

- Binning/Discretization: e.g., grouping tenure into tenure_group.

- Combining Features: e.g., total number of services per customer.

- Simplifying Categories: making features easier for models to interpret.

Feature Selection

- Using RandomForestClassifier feature importance to select the most relevant features.

Modeling Pipeline

- Using Scikit-Learn's ColumnTransformer and Pipeline for preprocessing, feature selection, and model training.

Model Comparison

- Quantitatively measure performance lift from feature engineering and selection.

## 📊 Model Performance
| Metric           | Baseline | Enhanced | Selected Features |
| ---------------- | -------- | -------- | ----------------- |
| Accuracy         | 0.80     | 0.81     | 0.81              |
| F1-Score (Churn) | 0.60     | 0.59     | 0.59              |


#### Observations

- Baseline Model: Trained on raw features.

- Enhanced Model: Trained with engineered features like tenure_group, num_add_services, and monthly_charge_ratio.

- Selected Features Model: Trained on a subset of engineered features selected using Random Forest feature importance (median threshold).

Key Findings:

- Feature engineering improved the model’s ability to predict churn (minority class).

- Feature selection using Random Forest importance did not significantly improve performance in this case.

- Performance differences highlight that feature selection effectiveness is dataset- and model-dependent.

## 🔑 Key Takeaways

Feature Engineering is Crucial
- Thoughtful feature creation often has a bigger impact on model performance than hyperparameter tuning or changing algorithms.

Feature Selection Requires Experimentation
- Different selection methods and thresholds may yield different results. Always test multiple approaches.

Understand Your Data
- Domain knowledge is essential for creating meaningful features and interpreting model results.

## 🧰 Technologies Used

- Python

- Pandas, NumPy

- Scikit-Learn (Pipeline, ColumnTransformer, RandomForestClassifier, SelectFromModel)

- Matplotlib & Seaborn (for visualization)

## ⚡ Conclusion

This project illustrates the power of feature engineering in predictive modeling and highlights that feature selection is not guaranteed to improve performance. By focusing on the data itself—through cleaning, engineering, and selection—you can build more powerful and interpretable models that provide actionable insights for business decision-making.

## 🛠 How to Run the Project
- Download
- Open on google colab or Jupyter Notebook
- Run all cells

## 👤 Author
Faheemunnisa Syeda Machine Learning & Applied Math Specialist

- 📧 syedafaheem7@gmail.com
- 🔗 GitHub: [https://github.com/syedafaheem7/]
- 🔗 linkedln: [https://www.linkedin.com/in/faheem-unnisa-s-6270888b/]
