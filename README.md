# health-life-expectancy
Predicting health life expectancy
# Overview:
This project explores the analysis, visualization, and regression techniques applied to the happiness dataset. The main goal is to build a model that predicts healthy life expectancy based on various attributes like country name, log GDP per capita, social support, freedom to make life choices, generosity, perceptions of corruption, positive affect, and negative affect. The project is conducted in a Jupyter Notebook and utilizes Python's data analysis and machine learning libraries.

Data Summary:
The dataset comprises several attributes/features related to happiness and life expectancy for different countries. Some of the attributes are continuous, such as log GDP per capita, social support, freedom to make life choices, generosity, perceptions of corruption, positive affect, and negative affect. Other attributes like country name and year are categorical.

Data Analysis and Visualization:
The project starts by summarizing the dataset, identifying the amount of data available, and distinguishing between continuous and categorical attributes. The statistical values for each attribute are computed, and visualizations (e.g., histograms) are generated to understand the distribution of each attribute. Notable traits and potential attributes requiring special treatment are discussed based on the visualizations.

Correlation Analysis:
Pearson Correlation Coefficient (PCC) is calculated to analyze the relationships between different data attributes and their correlation with the label (healthy life expectancy). Scatter plots are created to visualize these relationships, providing insights into the attribute interactions.

Data Splitting and Validation:
20% of the data is randomly selected for testing purposes. The data splitting process is explained, and its representativeness is verified, ensuring a fair evaluation of the model's performance.

Linear Regression with Regularization:
Two approaches are used to train a linear regression model: closed form solution (using the Normal Equation or SVD) and stochastic gradient descent (SGD). Additionally, Ridge, Lasso, and Elastic Net regularization techniques are applied, with different penalty term values. The impact of these regularization methods on model performance is examined, along with the influence of other hyperparameters like batch size and learning rate.

Polynomial Regression:
Polynomial regression is explored to check for overfitting or underfitting issues. The validation loss is analyzed to determine the model's performance.

Model Evaluation and Prediction:
The trained models are evaluated on the test data using appropriate evaluation metrics. The performance of each model is summarized, and the results are discussed. Future explorations and potential enhancements to improve performance are suggested.

Conclusion:
The project provides a comprehensive analysis of the happiness dataset, explores various regression techniques, and presents insights into the relationships between attributes and healthy life expectancy. By following the Jupyter Notebook, other data scientists or researchers can reproduce the results and extend the analysis further to gain a better understanding of happiness factors and improve the prediction models.
