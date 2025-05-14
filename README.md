🏡 House Price Prediction — Linear Regression Project
This project applies linear regression techniques to predict house prices using a dataset of housing features. It includes feature selection, regularization (Ridge Regression), and model evaluation based on accuracy and error metrics.

📚 For learning purposes only — not production-grade.

📌 Project Goals
- Build a regression model to predict house prices

- Explore and clean housing data

- Select meaningful features

- Handle multicollinearity

- Improve generalization using Ridge regularization

- Evaluate performance using R² and MSE

  📊 Features Used
The model uses the following features:

- Area: Total area of the property (in sq ft)

- Bedroom: Number of bedrooms

- Bathrooms: Number of bathrooms

- Parking: Number of parking spots

- Location: One-hot encoded (e.g., Urban, Suburb)

Condition: One-hot encoded (e.g., Good, Poor)

Note: Some features (like Age) were dropped due to high correlation and poor impact on model performance.
More dropped: Price per Sq Condition_Fair	RandomFeature2	RandomFeature1, irrelant and multicollinearity as well.

⚙️ Model Used
Linear Regression (Ridge Regression with Cross-Validation)

Scaled features using StandardScaler

Chose the best alpha via RidgeCV

📈 Performance
- Metric	      Value
- R² (Train)   	0.87
- R² (Test)    	0.61
- RMSE (Test)	  ~29,174
- Avg Price   	610,800
- Error Rate	 ~4.7%

🚀 What I Learned
How to identify and fix overfitting

How to handle multicollinearity using VIF

Using Ridge Regression to improve generalization

Evaluating models with R², MSE, RMSE


📌 Note
This is a simplified, linear solution. More advanced models like Random Forests or XGBoost could improve accuracy — but this project focuses on understanding linear modeling fundamentals.

