# Pokémon Generation Hypothesis Analysis

## Overview

This project aims to investigate the hypothesis that Pokémon in later generations are stronger based on their statistics. The analysis involves exploring Pokémon statistics across different generations, building predictive models to estimate Pokémon strength, and evaluating the performance of these models.

## Dataset

The dataset used in this project contains information about Pokémon, including their attributes such as HP, Attack, Defense, and Total stat. Each Pokémon is also assigned a Generation number indicating the generation it belongs to.

## Problem Statement

The main goal of this project is to determine if there's a correlation between Pokémon generations and their overall strength, as measured by their Total stat. This problem falls under supervised learning, specifically regression analysis.

## Methodology

- **Data Preprocessing:** The dataset is preprocessed to handle missing values, encode categorical features, and scale numerical features.

- **Model Building:** Various regression models are trained and evaluated using k-fold cross-validation. Hyperparameter tuning is performed using GridSearchCV to find the best-performing model configuration.

- **Model Evaluation:** The performance of the models is evaluated using mean squared error (MSE) as the scoring metric.

- **Visualization:** The results are visualized using scatter plots and bar charts to illustrate the relationship between Pokémon generations and their average total stat.

- **PCA Analysis:** Principal Component Analysis (PCA) is applied to investigate the impact of dimensionality reduction on model performance.

## Results

- The analysis reveals that there is a slight positive correlation between Pokémon generations and their average total stat.
- The best-performing model achieves a mean squared error (MSE) of X on the test set.
- PCA analysis shows that retaining 95% of the variance using TruncatedSVD leads to a slightly higher MSE compared to the baseline model.

## Conclusion

Based on the analysis, there is evidence to support the hypothesis that Pokémon in later generations tend to have higher overall strength, as measured by their Total stat. However, the relationship is not deterministic, and other factors may influence Pokémon strength as well.
