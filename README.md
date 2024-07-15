# Wine Quality Analysis

## Introduction

The quality of red and white wine is examined in this project. The chemical properties of wine, such as density, pH, sulfates, residual sugar, chlorides, citric acid, fixed and volatile acidities, density, and alcohol concentration, are investigated to assess wine quality. Consistency in wine quality is essential for maintaining a loyal customer base and ensuring commercial success in the competitive food and beverage sector.

## Dataset

The dataset used for this analysis is sourced from the UCI Machine Learning Repository. It comprises physicochemical properties and quality ratings of red and white wines. The dataset includes:

- **Red Wine**: 1,599 varieties
- **White Wine**: 4,898 varieties

Both datasets include 12 different properties of the wines, one of which is the quality based on sensory data, while the rest are chemical properties. Quality is an ordinal variable with a possible ranking from 1 (worst) to 10 (best).

### Dataset Files

- **Red Wine File**: `wine_red.csv`
- **White Wine File**: `wine_white.csv`

## Methods

### Data Preprocessing

1. **Combine Datasets**: Merging red and white wine datasets and adding a new column for wine type.
2. **Data Cleaning**: Checking for duplicates and missing values to ensure data integrity.
3. **Exploratory Data Analysis (EDA)**: Summary statistics, box plots, and histograms to investigate variable distributions and outliers.

### Analysis Techniques

1. **Regression Modeling**: To identify significant predictors of wine quality.
2. **Hypothesis Testing and ANOVA**: To test differences in quality ratings between red and white wines.
3. **Model Diagnostics**: To check assumptions like normality, independence, homoscedasticity, and linearity of residuals.
4. **Generalized Linear Modeling**: To further explore the relationships between predictor variables and wine quality.

### Tests Performed

1. **Hypothesis Testing**: t-test and randomization, testing for normality, independence, and equal variances.
2. **Confidence Intervals**: Relying on the Central Limit Theorem for large sample sizes.
3. **Bootstrapping**: To provide precision of mean quality rating estimates.
4. **Regression Analysis**: Including diagnostics of the model for residual normality and homoscedasticity.
5. **ANOVA**: Testing for normality, homogeneity of variances, and independence between groups.
6. **Model Selection**: Choosing the best fitting model using AIC value.

## Results

- **Key Physicochemical Properties**: Significant predictors of wine quality include alcohol content, volatile acidity, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and wine type.
- **Difference in Quality Ratings**: White wines generally have higher mean quality ratings than red wines.
- **Interactions and Nonlinear Relationships**: Further research is needed to fully understand the complex relationships between predictors and wine quality.

## Conclusions

- Wine quality is influenced by various physicochemical properties.
- White wines have slightly higher mean quality ratings compared to red wines.
- Practical implications include improving wine quality through optimized production processes and informed consumer choices.
- Further research is necessary to explore specific interactions and nonlinear relationships between variables and to expand the dataset for comprehensive insights.

## Future Research

1. **Exploration of Interactions and Nonlinear Relationships**: Using advanced statistical methods and machine learning.
2. **Incorporation of Additional Factors**: Including variables like grape type, fermentation methods, and geographic origin.
3. **Temporal Analysis and Longitudinal Studies**: Monitoring changes in wine quality over time.
4. **Cross-Cultural Studies and Consumer Preferences**: Understanding psychological, social, and cultural influences on wine preferences.
5. **Integration of Sensory Analysis**: Combining physicochemical data with sensory evaluations.
6. **Application of Advanced Modeling Techniques**: Improving prediction accuracy with machine learning algorithms.
7. **Impact of Environmental and Sustainable Practices**: Evaluating the effect of sustainable practices on wine quality.

## Running the Jupyter Notebook

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python libraries (pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels)

### Installation

Install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

### Running the Notebook

1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `Wine_Quality_Analysis.ipynb` notebook.
5. Run the cells in the notebook to perform the analysis.

   
## References

- UCI Machine Learning Repository: [Wine Quality Data Set](https://archive.ics.uci.edu/ml/datasets/wine+quality)
