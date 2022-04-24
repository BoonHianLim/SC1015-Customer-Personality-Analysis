# SC1015-Group9

### About: 
This is a Mini-Project for the course SC1015 (Introduction to Data Science and Artificial Intelligence). The dataset used in this project is extracted from [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). 

The source code, in order, are as follows:
1. [Data Exploration](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Data-exploratory.ipynb)
2. [Data Cleaning](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Data-cleaning.ipynb)
3. [Data Visualization](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Data-visualization.ipynb)
4. [Data Splitting](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Data-encoding-and-splitting.ipynb)
5. [Linear Regression](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Linear_Regression.ipynb)
6. [Poisson Regression](https://github.com/BoonHianLim/SC1015-Group9/blob/main/Poisson_Regression.ipynb)

### Contributors:
- __Lim Boon Hian__ - Data Exploration, Data Cleaning, Data Visualization
- __Lim Dong Wan__ - Linear Regression, Data Splitting
- __Marvell Ung Wew__ - Poisson Regression, Grid Search Cross Validation

### Problem Definition
Predicting customer sales using customer information

### Variables in Focus
__Response variables:__ TotalPurchase, MntGroceryProducts, MntWines, MntGoldProds

__Predictor variables:__
- _Categorical:_
    - Education
    - Marital_Status
    - HaveChild
    - YearRange
- _Numerical:_
    - Income
    - TotalChild
    - NumWebVisitsMonth

### Machine Learning Models Used
1. Linear Regression
2. Poisson Regression

### Insights and Recommendation
Main insight: The company utilizes customer-focused sales tactics with customer’s income as a guideline.

Recommendations:
1. Target audience should be customers who have / are:
    - fewer children
    - higher income
    - higher levels of education
    - born in 1940 - 1950
2. Improve online sales by upgrading company website, so as to make it more attractive and appealing to customers.

### Conclusion
1. __Customer income__ serves as the most important predictor to predict customer expenditure
2. *Linear Regression* yield __better__ results than *Poisson Regression*
3. GridSearch CV only __marginally__ improved the Linear Regression model

### Things Learnt
1. K-fold splitting
2. Poisson Regression
3. Plotly subplot
4. Grid Search Cross Validation
5. Altair interactive plot
6. Get dummy values for categorical variables in Linear Regression
7. Collaborating on Github :)

### References
- <https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis> (Original Dataset)
- <https://ntulearn.ntu.edu.sg/webapps/blackboard/content/listContent.jsp?course_id=_2606895_1&content_id=_2762960_1>
- <https://stackoverflow.com/questions/21912634/how-can-i-sort-a-boxplot-in-pandas-by-the-median-values>
- <https://altair-viz.github.io/gallery/index.html>
- <https://www.kaggle.com/code/jnikhilsai/cross-validation-with-linear-regression/notebook>
- <https://towardsdatascience.com/gridsearchcv-for-beginners-db48a90114ee>
- <https://machinelearningmastery.com/rfe-feature-selection-in-python>
- <https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html>
- <https://medium.com/lcc-unison/how-to-poisson-regression-model-python-implementation-1c672582eb96>
- <https://timeseriesreasoning.com/contents/poisson-regression-model>
- <https://matplotlib.org/stable/gallery/subplots_axes_and_figures/subplots_demo.html> 
- <https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html> 
- <https://medium.com/analytics-vidhya/implementing-linear-regression-using-sklearn-76264a3c073c> 
- <https://machinelearningmastery.com/rfe-feature-selection-in-python/> 
