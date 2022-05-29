# Microsoft_Engage
[HERE](https://youtu.be/Bgdtak8vZVE) IS THE LINK FOR THE DEMO VIDEO OF MY PROJECT!!
1) df.nunique() returns the number of categories each column has.

2) if a column has more then 50% null values then we simply drop the column.

3) .value_counts() returns the categories with the frequency of occurrence. 

4) I manually checked the null values in the make column many of the models were Mercedes. So, I replaced the null values with Benz and changes the 'make' value for rest of the models like roll Royce and go+.

5) To handle with high number of features I divided the entire attributes into various classes.

6) There are 5 classes for the categorical features and 2 classes for the numerical features.

7) Created a new data frame 'new_df' to work with the features that we are interested in. 

8) Replaced the null values in the categorical features with the mode of the respective columns and for numerical features the nulls are replaced with mean.

9) encoded the categorical features into numerical values.

10) Used seaborn library for data analysis. 

11) Heat maps for various class of features were drawn and the irrelevant features were dropped.

12) Pair plots are drawn to check the variation between various features within a class. 

13) distplot and catplot are used to check the variation of entire data of a particular column.

14) There are our final features that we are interested in. I used the inbuilt train_test_split to get validation data, training data and test data. 

15) Used sklearn linear regressor to estimate the dependency of each feature. We can set the threshold of the coefficients with a particular value and choose the features that are effective in prediction. 

16) Used randomforest for better estimation.

17)  Now I gonna predict the price of the car using the 4 atmost important features (I believe). 

18) used onehot encoding to convert the categorical features into numericals.

19) Used random forest classifier to predict the price. We can use Linear regressor aswell.

20) We can test with various kind of inputs to predict the price.
