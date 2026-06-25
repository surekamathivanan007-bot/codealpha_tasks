# Task 1 - Iris Flower Classification

**Internship:** CodeAlpha (Data Science / Machine Learning Track)
**Intern:** Sureka Mathivanan

## Objective
Use measurements of Iris flowers (setosa, versicolor, virginica) to train a machine learning model that classifies the species based on those measurements. Evaluate accuracy and performance, and understand basic classification concepts.

## Methodology

1. **Load Dataset** – used Scikit-learn's built-in Iris dataset (no manual download needed)
2. **Exploratory Data Analysis** – visualized sepal and petal measurements across species
3. **Train/Test Split** – held out 20% of data for unbiased evaluation
4. **Model Training** – compared Decision Tree, Random Forest, and SVM classifiers
5. **Model Evaluation** – accuracy, precision, recall, F1-score, and confusion matrix
6. **Feature Importance** – identified which measurements matter most for classification

## Key Findings
- Petal length and petal width separate the three species far more clearly than sepal measurements
- Setosa is almost perfectly distinguishable from the other two species
- Versicolor and virginica show some overlap, which shows up as minor confusion in the model's predictions
- SVM (linear kernel) achieved the highest accuracy on this dataset

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Decision Tree, Random Forest, SVM)
- Jupyter Notebook
