# Wine Quality Case Study

## Project Overview
This project analyzes the Wine Quality dataset to uncover the significant features that determine or affect the quality ratings of wine. The study also explores the differences between red and white wines based on various characteristics, such as sugar content, acidity, and more.

## Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- **Description:** The dataset consists of chemical properties of red and white variants of Portuguese "Vinho Verde" wine. The data includes variables like fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and the quality rating.

## Objectives
- **Feature Analysis:** Identify the key features that most significantly affect the quality ratings of wine.
- **Comparison:** Differentiate between red and white wine based on their chemical properties.
- **Predictive Modeling:** Develop models to predict wine quality based on the identified features.

## Methodology
1. **Data Preprocessing:** 
   - Handling missing values, outliers, and scaling features.
   - Data splitting into training and testing sets.
   
2. **Exploratory Data Analysis (EDA):**
   - Visualizing the distribution of features.
   - Analyzing correlations between features and wine quality.
   
3. **Feature Selection:**
   - Identifying the most influential features using statistical techniques.
   - Comparing feature importance between red and white wines.
   
4. **Modeling:**
   - Implementing machine learning models like Linear Regression, Decision Trees, and Random Forests.
   - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
   
5. **Result Interpretation:**
   - Analyzing model outcomes to determine key factors influencing wine quality.
   - Highlighting the differences between red and white wines.

## Results
- **Key Features:** The most influential features identified include alcohol content, volatile acidity, and sulphates.
- **Red vs. White Wine:** Red wine tends to have higher levels of volatile acidity and sulphates, while white wine generally has a higher sugar content.

## Tools & Technologies
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Visualization:** Tableau, Matplotlib, Seaborn
- **Statistical Analysis:** Correlation analysis, Feature importance

## Conclusion
This case study provides valuable insights into the factors that affect wine quality and highlights the chemical differences between red and white wine. The findings can help winemakers and consumers better understand the characteristics that contribute to a high-quality wine.

## Future Work
- **Model Enhancement:** Experiment with more advanced machine learning models to improve prediction accuracy.
- **Dataset Expansion:** Analyze a larger dataset or incorporate other types of wine for a more comprehensive study.
- **Feature Engineering:** Explore additional features such as wine aging or geographical origin.

## Author
Prabhav Jain
