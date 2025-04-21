# Machine Learning Master Class Project: Final Project

## Team Members
- **Hugo Dutra**
- **Zuzanna Rybok**
- **Mateusz Janowski**

## Overview
This project implements advanced machine learning techniques, including Generalized Additive Models (GAMs), Decision Trees, Random Forests, Support Vector Machines (SVMs), Principal Component Analysis (PCA), and Reinforcement Learning with Q-Learning. The focus is on exploring these methods to build predictive models for vegetation classification through feature selection and dimensionality reduction.

## Table of Contents
1. [Project Description](#project-description)
2. [Datasets](#datasets)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Methods](#methods)
6. [Project Structure](#project-structure)

## Project Description
The project explores various machine learning approaches for vegetation classification. It implements and compares different feature selection techniques, dimensionality reduction methods, and classification algorithms to establish a comprehensive methodology for environmental data analysis.

## Datasets
- Working with three primary datasets: `df_1`, `df_2`, and `df_4`
- Target variable: **Vegetation_Type**
- Features include topographic data and soil characteristics

## Installation
Required Python packages:

```bash
pip install pandas numpy scikit-learn scipy matplotlib seaborn
```

## Usage
To run the project:

```bash
git clone [repository-url]
cd [project-directory]
jupyter notebook Project2.ipynb
```

## Methods

### Feature Selection Techniques

#### Reinforcement Learning Approach
- Q-Learning implementation for feature selection
- Two versions of Q-Learning agents:
  - Baseline agent with standard Q-table
  - Improved agent with feature importance integration
- Epsilon-greedy exploration strategy
- Custom reward function based on model performance

#### Traditional Feature Selection
- Random Forest feature importance analysis
- Correlation analysis
- Feature ranking based on importance scores

### Classification Models

#### Linear Models
- Generalized Additive Models (GAMs)
- Lasso Classifier
- ElasticNet Classifier
- Logistic Regression with CV

#### Tree-based Models
- Decision Trees
- Random Forest Classifier
  - Hyperparameter tuning
  - Feature importance analysis

#### Support Vector Machines
- RBF kernel implementation
- Grid search for hyperparameter optimization
- Cross-validation strategy

### Dimensionality Reduction

#### Principal Component Analysis (PCA)
- Two implementations:
  - 18-feature dataset
  - 55-feature dataset
- Variance retention analysis
- Component selection methodology

## Project Structure
GAM's
Decision Trees
Random Forest
PCA
Reinforcemente Learning


## Development Workflow
1. Data preprocessing and feature engineering
2. Implementation of feature selection methods
3. Model development and training
4. Dimensionality reduction analysis
5. Model evaluation and comparison
6. Documentation and code organization

## Contributing
To contribute to this project:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
MIT
