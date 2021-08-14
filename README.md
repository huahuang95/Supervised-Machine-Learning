# Supervised-Machine-Learning

## Melbourne Housing Price Prediction
Team project for Supervised-Machine-Learning (BA810)

### Data Source
- Kaggle: [Melbourne Housing Market](https://www.kaggle.com/anthonypino/melbourne-housing-market)

### Project Objectives
- Build several supervised machine learning models and predict housing prices in Melbourne.
- Find important variables that influence the prices the most and provide advice to buyers and sellers.
- Apply **Linear Regression, Ridge Regression, Lasso Regression, Bagging (Bootstrap aggregating), Random Forest, and Boosting** to see which one performs the best in terms of price prediction.

### Project Summary
- According to the exploratory data analysis, we learned that some patterns or relationships exist among the location’s features and house prices, such as Regionname; and the houses far from CBD tend to have lower prices. After we execute several models, variable CouncilArea does strongly affect the house prices.
- After comparing all the models, the results indicate that CouncilArea has a stronger effect on Melbourne’s housing price than other features.
- Comparing all the models with test MSE, the decision tree has the highest test MSE, followed by Ridge, Lasso, linear regression, and bagging. Comparatively, random forests and boosting have much lower test MSE, indicating better performance in prediction.
- If we compare the last two models, random forests and boosting, they excel in different areas. Random forest tends to perform better with data with a lot of statistical noise. While boosting tends to perform with unbalanced data, which was reduced due to our scaling.

*By Chiebuka Onwuzurike, Tzu-Hua Huang, Yangyang Zhou, Yichi Zhang*
