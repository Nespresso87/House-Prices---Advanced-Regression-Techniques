# House Prices Prediction - Advanced Regression Project

## Overview
This project implements an advanced regression model to predict house prices in Ames, Iowa, using a comprehensive dataset of 79 explanatory variables. The implementation focuses on sophisticated feature engineering, statistical analysis, and robust model evaluation techniques.

## 🎯 Project Goals
- Predict house sale prices using advanced regression techniques
- Implement creative feature engineering approaches
- Handle complex real-estate data with multiple variable types
- Achieve competitive RMSE scores on the logarithm of price predictions

## 🔑 Key Features
1. **Comprehensive Feature Engineering**
   - Age-related feature calculations
   - Quality feature encoding
   - Interaction terms generation
   - Neighborhood effect analysis
   - Missing value handling

2. **Statistical Analysis**
   - Correlation analysis
   - Variance Inflation Factor (VIF) calculation
   - Feature importance assessment
   - Neighborhood effects evaluation

3. **Model Evaluation**
   - RMSE on log-transformed prices
   - R-squared and Adjusted R-squared
   - AIC and BIC metrics
   - Feature significance analysis

## 📦 Requirements
```
pandas
numpy
scikit-learn
statsmodels
matplotlib
```

## 🚀 Getting Started
1. Clone this repository
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Place your data files in the project directory:
   - train.csv
   - test.csv
4. Run the main script:
   ```bash
   python house_price_prediction.py
   ```

## 📊 Data Structure
The model expects training and test data with the following key features:
- Numerical features (e.g., GrLivArea, TotalBsmtSF)
- Categorical features (e.g., Neighborhood)
- Quality ratings (e.g., ExterQual, KitchenQual)
- Temporal features (e.g., YearBuilt, YrSold)

## 🛠️ Model Components

### Feature Preparation (`prepare_features`)
- Handles missing data
- Creates derived features
- Implements one-hot encoding
- Generates interaction terms

### Statistical Analysis
- `analyze_correlations`: Identifies highly correlated features
- `calculate_vif`: Detects multicollinearity
- `analyze_neighborhood_effects`: Assesses location impact

### Prediction Pipeline
- Feature scaling
- Model fitting
- Prediction generation
- Submission file creation

## 📈 Output
The script generates:
1. Detailed model performance metrics
2. Neighborhood effect analysis
3. Feature importance visualization
4. Kaggle submission file (CSV)

## 📝 Submission Format
The final output follows Kaggle's required format:
```csv
Id,SalePrice
1461,169000.1
1462,187724.1233
1463,175221
```

## 🔍 Model Evaluation
The model is evaluated using:
- RMSE on log-transformed prices
- R-squared and Adjusted R-squared
- AIC (Akaike Information Criterion)
- BIC (Bayesian Information Criterion)

## 📊 Visualization
The project includes visualization of:
- Neighborhood effects
- Feature correlations
- Model diagnostics

## 🤝 Contributing
Feel free to:
1. Fork the repository
2. Create a feature branch
3. Submit pull requests with improvements

## 🎓 Educational Context
This project is ideal for:
- Data science students post-online course
- Practitioners learning advanced regression
- Feature engineering practice
- Real-world data handling experience

## 📚 Acknowledgments
- Dataset: Dean De Cock's Ames Housing dataset
- Competition Platform: Kaggle
- Original photo by Tom Thain on Unsplash

## 📜 License
[MIT License](LICENSE)

## 🔗 Additional Resources
- [Kaggle Competition Page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- [Ames Housing Dataset Documentation](link-to-documentation)
- [Feature Engineering Guide](link-to-guide)# House-Prices---Advanced-Regression-Techniques
