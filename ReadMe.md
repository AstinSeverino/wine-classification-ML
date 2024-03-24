# Wine Quality Prediction 🍷

## About The Project

This project aims to explore and predict the quality of Portuguese "Vinho Verde" wine using Decision Tree and Random Forest algorithms in a Jupyter Notebook. The focus is on both red and white wine variants, leveraging physicochemical properties to predict sensory quality without access to information like grape types or brand names.

### Context

The datasets for red and white wine variants contain several physicochemical (inputs) and one sensory (output) variable, offering a foundation for either classification or regression tasks. Notably, the classes are ordered but unbalanced, highlighting the presence of more normal wines compared to excellent or poor ones.

🔗 [Dataset Source - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality)

### Content

- **Input Variables:**
  1. Fixed acidity
  2. Volatile acidity
  3. Citric acid
  4. Residual sugar
  5. Chlorides
  6. Free sulfur dioxide
  7. Total sulfur dioxide
  8. Density
  9. pH
  10. Sulphates
  11. Alcohol
  
- **Output Variable:**
  - Quality (score between 0 and 10)

### Inspiration

The goal is to determine which physicochemical properties most significantly impact wine quality. By implementing machine learning models, we can identify the features that contribute to a wine being classified as 'good'.

## Getting Started

To run this project, ensure you have Jupyter Notebook installed and can access the wine quality datasets.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries: pandas, numpy, sklearn, matplotlib


