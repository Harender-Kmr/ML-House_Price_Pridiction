# ML-House_Price_Pridiction
This is very first/common regression problem in Machine Learning and very important one.
In this specific problem i am working on Boston house dataset, have 506 instance of house having 14 attribute(features). For complete information people can check housing.names file for complete description of the 
Data used.

In this particular Problem i first load the dataset using pandas library.
and perform basic operation i.e. describe, shape, info to get the overview of the Data, this is small dataset but procedure is completely same for bigger dataset as well.
You can check my other regression problem that i worked on large data with total 81 features.

I performed EDA analysis to visualize the features and their distribution, calculate the correlated matric, to find if features have high correlation and do the treatment accordingly

In any machine learning problem dealing wiht Null values and Outliers is very importment as it will affect your model performace drasticaly.
so i take care for those and performed required treatment. impute the null values with median.

Then i split the dataset so that i can also validate my results. and using mean square error as a matrics to measure the model performance.

i used, linear Regressor, Desicion Tree Regressor and Random Forest Regressor for this particular problem. and Random Forest Regressor gives me better mse on the validation set.

Then i drop the model in Dragon.joblib to use it later.

Wwe can tune the model hyperparameter furture to improve the model performation. but in this problem i wanted to keep the problem simple.

