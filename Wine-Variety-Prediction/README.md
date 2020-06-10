# Summary
## Wine Variety Prediction
The objective of the project is build a predictive model for predicting the wine variety. This is multi-class classification problem have 28 classes or wine varieties.


### The Data Description is as follows:
* user_name - user_name of the reviewer
* country -The country that the wine is from.
* review_title - The title of the wine review, which often contains the vintage.
* review_description - A verbose review of the wine.
* designation - The vineyard within the winery where the grapes that made the wine are from.
* points - ratings given by the user. The ratings are between 0 -100.
* price - The cost for a bottle of the wine
* province - The province or state that the wine is from.
* region_1 - The wine-growing area in a province or state (ie Napa).
* region_2 - Sometimes there are more specific regions specified within a wine-growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank.
* winery - The winery that made the wine
* variety - The type of grapes used to make the wine. Dependent variable for task 2 of the assignment.

## Approach to the problem
* Firstly, we prepare dataset for EDA and feature engineering. In data prepartion we divided our dataset into three categories text, categorical and numerical feature than removing variables which not helpfull in prediction and imputed the missing data.
* we perform some insightfull exploratory data analysis.
### Feature Extracted
* Categories point variables.
* Transform price variable into log
* Label encoding of the categorical feature including target or wine variety
* Get TF-IDF vectorizer of text variable (reviews)
### Model
* Using Random forest classifier
* 5 K-Fold Cross Validation ~ f1 score 0.93
* Validation set ~ f1 score 0.94
## Top 5 actionable Insights from the Data
*  Positive relationship between price and point that means as price increases, point also increase but, the highest prices isn't of the wine with highest point.
* The average point 89 and average price the wine is 37
* US, Italy, and France are the larger producer of wine.
* The average price of wine of Italy is highest compare to the other counties
* And wine of Italy and france get highest average points compare to the other counties.
