# Project Title: Bayesian Analysis of NFL Sports Betting Outcomes

## Overview
This project explores win probability prediction in NFL sports betting using Bayesian hierarchical models, logistic regression, and random forest models. The study aims to analyze historical game data, assess team strengths, and identify mispriced betting odds through probabilistic modeling.

## Key Features
- **Bayesian Hierarchical Model**:
  - Estimates team strengths and win probabilities with uncertainty quantification.
  - Iteratively updates predictions as new game data becomes available.
- **Comparative Modeling**:
  - Benchmarked Bayesian models against logistic regression and random forest.
  - Highlighted strengths and limitations of parametric and non-parametric approaches.
- **Comprehensive Data Analysis**:
  - Processed weather, game-specific, and spread data with a multi-layered imputation strategy.
  - Explored scoring patterns, home-field advantage, and weather impacts on outcomes.

## Tools and Technologies
- **Python Libraries**:
  - Pandas and NumPy for data processing.
  - Matplotlib and Seaborn for visualizations.
  - PyMC3 for Bayesian modeling.
  - Scikit-learn for regression and random forest models.
- **Jupyter Notebook**:
  - Organized workflow for data cleaning, EDA, and modeling.

## Workflow
1. **Data Cleaning**:
   - Imputed missing weather and game-specific data using granular trends.
   - Standardized features for modeling.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized relationships between scores, spreads, and weather conditions.
   - Highlighted distribution trends and key patterns.

3. **Model Development**:
   - Implemented Bayesian models to estimate win probabilities.
   - Built logistic regression and random forest models for comparison.

4. **Results Evaluation**:
   - Assessed model performance using Brier score, log-loss, and accuracy.
   - Plotted calibration curves and analyzed model biases.

## Results
- **Model Performance**:
  - Bayesian model achieved balanced calibration and predictive accuracy.
  - Logistic regression excelled in probabilistic accuracy but lacked nuance in interactions.
  - Random forest captured complex patterns but underperformed in calibration.
- **Insights**:
  - Home-field advantage and spread magnitude were significant predictors of outcomes.
  - Bayesian estimates revealed distinct team strength variability, highlighting its robustness in dynamic environments.

### Example Visuals:
- Calibration curves for model comparison.
- Scatter plots of total scores against weather conditions.
- Team strength estimates by Bayesian modeling.

## Future Enhancements
- Incorporate betting odds as features for better market bias analysis.
- Expand analysis to include additional seasons and teams.
- Explore ensemble modeling to combine strengths of different approaches.
