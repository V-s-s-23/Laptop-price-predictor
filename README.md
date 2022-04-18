# Laptop-price-predictor/Regression based model:-
-> Build a model that predicts the price of the laptop given the configurations.

-> using Linear, Lasso, and Random Forest Regressors to get the best model.

# Feature Engineering:- 
 Go through all the features one by one and keep adding new features. I have made the following changes and created new variables:
 
.ScreenResolution - Made columns for names of, Touchscreen, ips panel,screen reselution. 

.PPI(pixcel per inches) - made column ppi from  resolution and inches column.

.CPU - made 2 columns , cpu brand and cpu name.

.Memory - made different columns - hdd,sdd,hybrid,flashstorage.

.Processor - Made columns for Name of the Processor, Type of the Processor, Generation. 

There are some more columns like - GPU ,Opys(operating system) etc.

# Data Preprocessing:-
There are a few columns which are categorical and convert them into numerical type by OneHotEncoder.

# Exploratory Data Analysis:-
Perfoming EDA to get insights from data.

# Model Building:-
Traditional Method -
Used scikit-learn library for the Machine Learning tasks. Applied onehotencoder and converted the categorical variables into numerical ones.Then I splited the data into training and test sets with a test size of 20%. I tried three different models ( Linear,Ridge and Lasso Regression, Random Forest Regression) and evaluated them using Mean Absolute Error and r2_score.
I also used pipeline and column transformer.
