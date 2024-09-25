# Red Wine Quality Data - Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis (EDA) on the Red Wine Quality dataset, which contains information about various physicochemical properties of red wine and their corresponding quality ratings. The goal is to extract meaningful insights from the data and explore correlations between the features and wine quality.

## Dataset Overview

The dataset used for this analysis is the **Red Wine Quality** dataset, available from the UCI Machine Learning Repository. It includes several variables related to the chemical composition of red wine, such as acidity, sugar content, pH levels, and alcohol, as well as a quality rating (target variable) on a scale of 0 to 10.

### Features in the dataset:
- **fixed acidity**: Tartaric acid levels in wine (g/dm³)
- **volatile acidity**: Acetic acid content, responsible for vinegary taste (g/dm³)
- **citric acid**: A component found in small quantities, adds 'freshness' to wines
- **residual sugar**: Sugar remaining after fermentation (g/dm³)
- **chlorides**: Salt content in wine (g/dm³)
- **free sulfur dioxide**: Free form of SO2 in wine (mg/dm³)
- **total sulfur dioxide**: Bound and free forms of SO2 in wine (mg/dm³)
- **density**: Density of wine (g/cm³)
- **pH**: Describes how acidic or basic wine is
- **sulphates**: Wine preservative, related to SO2 (g/dm³)
- **alcohol**: Alcohol content in wine (% by volume)
- **quality**: Target variable (integer, ranges from 0 to 10)

## Objective
The primary objective of this project is to:
- Explore the dataset’s structure, summary statistics, and distribution.
- Visualize relationships between different features and the wine quality.
- Identify important factors that contribute to wine quality.
- Provide insights into correlations and trends.

## Steps Performed in the Analysis

1. **Data Loading & Inspection**:
    - Imported the dataset using `Pandas` and checked for missing values.
    - Examined the dataset shape and data types of each column.
    - Displayed summary statistics using `describe()` function.

2. **Data Cleaning**:
    - Handled missing or incorrect data (if present).
    - Converted data types as required for analysis.

3. **Univariate Analysis**:
    - Visualized the distribution of individual features like acidity, alcohol, etc., using histograms and KDE plots.
    - Analyzed summary statistics like mean, median, and standard deviation.

4. **Bivariate Analysis**:
    - Explored correlations between different features and wine quality.
    - Used scatter plots and heatmaps to observe patterns between wine attributes and quality ratings.

5. **Multivariate Analysis**:
    - Created pairplots and multivariate visualizations to understand the relationships among more than two features.

6. **Correlation Analysis**:
    - Generated a correlation matrix to quantify the relationships between different variables.
    - Focused on identifying the features that are most correlated with wine quality.

7. **Visualizations**:
    - Used `Seaborn` and `Matplotlib` to create detailed visualizations like bar charts, box plots, and violin plots.

## Results and Insights

- **Alcohol**: A higher alcohol percentage seems to contribute to a higher quality rating.
- **Volatile Acidity**: High levels of volatile acidity negatively impact the wine quality.
- **Sulphates**: Wines with a higher sulphate content tend to have better quality ratings.
- **Citric Acid**: Wines with a moderate amount of citric acid also score higher on the quality scale.
  
## Technologies Used

- **Python**: For data manipulation and analysis.
- **Pandas**: To load and preprocess the data.
- **Seaborn & Matplotlib**: For data visualization.
- **Jupyter Notebook**: For interactive data analysis and visualizations.

## Conclusion

The EDA revealed several interesting relationships between the physicochemical properties of red wine and its quality. Key factors like alcohol content, volatile acidity, and sulphates showed strong correlations with wine quality, offering insights into what contributes to higher quality wine. These insights could be used to further improve wine production processes.
