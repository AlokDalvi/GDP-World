# GDP-World

This code performs an analysis of the World GDP dataset to explore the factors affecting the GDP per capita of different countries. It includes data preprocessing, visualization, and machine learning modeling techniques.

## Dependencies

The code requires the following libraries to be installed:
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

## Running the Code

To run the code, follow these steps:
1. Make sure you have the required dependencies installed.
2. Download the "gdpWorld.csv" dataset and save it in the same directory as the code file.
3. Open the code file in a Python environment.
4. Run the code and wait for the analysis to complete.

## Code Description

The code performs the following steps:
1. Loads the dataset and preprocesses the data.
2. Conducts exploratory data analysis, including visualizations and correlation analysis.
3. Divides the data into training and test sets for machine learning modeling.
4. Applies linear regression and random forest regression models to predict GDP per capita.
5. Evaluates the performance of the models using metrics such as RMSE and R2 score.
6. Visualizes the predicted GDP per capita and compares it with the ground truth values.
7. Generates additional visualizations to analyze the relationship between different factors and GDP per capita.

## Results

The analysis reveals several factors that have a significant correlation with GDP per capita, such as phones per 1000 people, net migration, and industry. The random forest regression model achieves a higher R2 score and lower RMSE compared to the linear regression model.

## Limitations

It's important to note that this analysis has certain limitations, such as the assumption of linearity in the linear regression model and the potential impact of outliers on the results.

## Contact Information

For any questions or feedback, please contact [your email address].

## References

- [Dataset source: World GDP Dataset](link)
- [Scikit-learn documentation](link)
