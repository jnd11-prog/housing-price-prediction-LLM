Housing Price Prediction 

A Python data science project exploring how property features can help estimate home sale prices in Ames, Iowa.
Project Goal
Can housing data help identify properties worth investigating as potentially underpriced?
This project explores that question through data analysis, decision tree modeling, and validation. It also considers what a model would need before supporting real investment decisions.
Dataset
The project uses Kaggle’s House Prices dataset, containing 1,460 training examples and 79 explanatory variables. The prediction target is SalePrice.
The initial model focuses on five features:
Feature	Description
GrLivArea	Above-ground living area
YearBuilt	Original construction year
BedroomAbvGr	Above-ground bedrooms
FullBath	Full bathrooms above ground
LotArea	Lot size
Tools
* Python — analysis and modeling
* pandas — loading and exploring data
* Matplotlib — visualizing distributions
* scikit-learn — decision tree regression and evaluation
* Kaggle Notebooks — development environment
Approach
1. Explore the dataset and examine sale-price distributions.
2. Select property features for an initial decision tree model.
3. Split labeled data into training and validation sets.
4. Evaluate predictions using mean absolute error (MAE).
5. Interpret model limitations and identify opportunities for improvement.
   
Evaluation

MAE measures the average absolute difference between predicted and actual sale prices, expressed in dollars. Lower values indicate smaller average errors.
Performance on held-out validation data matters more than performance on homes the model has already seen. Kaggle’s separate test.csv does not include sale prices, so local validation uses a split of the labeled training data.

Results will be documented alongside the completed notebook.
Business Perspective
A predicted price above a listing price could flag a property for further research, but it does not establish that the property is a good investment. Renovation costs, transaction costs, property condition, and current market conditions would also need to be considered.
Next Steps
* Compare the decision tree with a random forest.
* Explore additional features, including neighborhood and overall quality.
* Investigate where prediction errors are largest.
* Document validation results and recommendations.
Project Context
Developed as part of the Possible data science project.
Author: Jana Shelomi N. Domingo
