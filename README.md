# Titanic-Problem--EDA-VEDA-ML
A systematic solution for Titanic problem:

In more details the followings are performed:


1. Data Imprt using pandas

2. Exploratory data analysis for numerical and categorical variables, using pandas methods: info(), describe(), quantile()

3. Some sql queries are performed on the dataframes using Ipythonsql package.

4. Feature analysis is performed using large utilizatio of groupby and aggregate functions.

5. Visual Explatory data analysis is performed using seaborn's FacetGrid, matplotlib.plyplot's hist.

6. Feature engineering is performed by categorizin numerical features , using qcut, and nuermizing categoical features using map method.

7. Some Tableu visualization is also performed for A/B testing of different clases whose IFrame is added.

8. Feature engineering is also performed by providing additional faetures, using regex's replace, extract, and the statistical significance of the new features are checked using chi-square test.

9. Several classifiers are hypertuned and gridsearched using sklearns GridSearchCV, namely, Random Forest, Decision Tree, Support Vector Machine, K-Nearest Neighbor, Logistic Regression, and Perceptron.

10. The level of importance of features are studied using random forest's feature importance method and it turned out that one of the engineered features came on top.

11. Models are evaluated and random forest showed highest accuracy.

12. Chosen model is submitted and 79% accuracy and top 25% competitor location is achieved.
