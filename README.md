🏡 Linear Regression Project for Predicting Home Prices
Using a dataset of housing characteristics, this project uses linear regression techniques to forecast home prices. Feature selection, regularization (Ridge Regression), and model evaluation using accuracy and error metrics are all included.


📚 Not production-grade, just for educational purposes.



📌 Project Objectives: Construct a regression model to forecast home values

 Examine and purify housing data
 Choose features that are important.
 Manage multicollinearity
 Ridge regularization can be used to enhance generalization.
 Utilize R2 and MSE to assess performance.
 

Features Employed
 The following features are used by the model:
  1.Area: The property's total area (in square feet)
  
  2.Bedroom: The quantity of bedrooms
  
  3.The quantity of restrooms
  
  4.Parking: The quantity of parking spaces
  
  5.Location: One-hot encoded (suburban, urban, etc.)
  
  6.Condition: One-hot encoded (Good, Poor, etc.)

 Note: Age was one of the features that was removed because

 Note: A few features, such as Age, were eliminated because of their poor influence on model performance and high correlation.
 Price per Sq Condition_Fair RandomFeature2 RandomFeature1 irrelant and multicollinearity were also dropped.
 

 ⚙️ Linear regression (Ridge regression with cross-validation) was the model used.

-StandardScaler was used to scale features.

-used RidgeCV to select the optimal alpha.

📈 Performance
- Metric	      Value
- R² (Train)   	0.87
- R² (Test)    	0.61
- RMSE (Test)	  ~29,174
- Avg Price   	610,800
- Error Rate	 ~4.7%

🚀 What I Learned:

How to recognize and correct overfitting

How to use VIF to manage multicollinearity

Enhancing generalization through the use of Ridge Regression

Model evaluation using R2, MSE, and RMSE


📌 Take note that this is a linear, simplified solution. Accuracy could be increased by using more sophisticated models like Random Forests or XGBoost, but the goal of this project is to comprehend the foundations of linear modeling.
