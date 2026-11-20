# Iris Flower Analysis 🌸

## Project Overview
A Data Science project focused on analysing the Iris flower dataset, exploring flower measurements, creating visualizations, and building a machine learning model to classify flower species.

## Dataset
- **Rows:** 150 (original dataset)
- **Columns:** 5
- **Species:** Setosa, Versicolor, Virginica
- **Final cleaned records:** 149

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Work

1. Loaded and explored the Iris dataset.
2. Performed data cleaning and preprocessing.
3. Checked missing values and removed one duplicate record.
4. Performed Exploratory Data Analysis (EDA).
5. Calculated statistical measurements using Pandas and NumPy.
6. Created visualizations:
   - Species Count Plot
   - Sepal Length Histogram
   - Petal Length vs Petal Width Scatter Plot
   - Petal Length Box Plot
   - Correlation Heatmap
7. Built a Random Forest Classification model.
8. Evaluated the model using accuracy and a classification report.

## Model Results
- **Algorithm:** Random Forest Classifier
- **Training Data:** 119 records
- **Testing Data:** 30 records
- **Test Accuracy:** 100%

All 30 test samples were classified correctly on the selected train-test split.

## Key Insights
- The dataset contains three Iris flower species.
- No missing values were found.
- Petal length and petal width help distinguish flower species.
- Setosa generally has the shortest petals, while Virginica has the longest.

## Project Files
- `iris.csv` – Original dataset
- `Task_4_Iris_Flower_Analysis.ipynb` – Jupyter Notebook containing the analysis and model
- `Task_4_Iris_Flower_Analysis_Report.docx` – Project report

## Conclusion
This project provided practical experience in data analysis, visualization, preprocessing, and machine learning using Python. The Random Forest model achieved 100% accuracy on the selected test dataset.

## Dataset Source
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv
