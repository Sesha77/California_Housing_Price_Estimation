California_Housing_Price_Estimation
This project, California Housing Price Estimation, focuses on predicting median house values in California using the California Housing dataset from Scikit-learn. It demonstrates a complete data science pipeline—from data loading and preprocessing to building and evaluating a linear regression model.

The dataset contains information collected from the 1990 California census, featuring attributes like average number of rooms, population, median income, and housing age per block group. These features are used to predict the target variable: the median house value for each block group.

We start by loading the dataset and converting it into a pandas DataFrame for easier handling. Exploratory Data Analysis (EDA) is performed to understand the structure of the data and the relationships between features. The project checks for missing values, visualizes feature distributions using seaborn, and examines correlations through a heatmap.

After EDA, the dataset is split into training and testing sets. Standardization is applied using StandardScaler to ensure all features are on the same scale. A simple Linear Regression model from Scikit-learn is trained on the data. We then evaluate the model’s performance using metrics such as Mean Squared Error (MSE) and R-squared (R²) score.

This project provides a basic yet comprehensive foundation for beginners in machine learning and data analysis. It emphasizes the importance of data preprocessing and evaluation while offering a practical application of regression techniques. While linear regression may not be the best algorithm for real-world price prediction due to its simplicity, it serves as a good starting point for understanding model development and performance interpretation.

