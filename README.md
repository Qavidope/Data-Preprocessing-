# Data science 
Data-Preprocessing-


 Techniques used in data preprocessing:

Data Cleaning: This step involves handling missing values, dealing with outliers, and removing or correcting any inconsistencies or errors in the data.

Data Integration: In some cases, data may be spread across multiple sources or files. Data integration involves combining the data from different sources into a single dataset.

Data Transformation: Data transformation involves converting the data into a suitable format for analysis. This may include scaling numeric variables, encoding categorical variables, and transforming skewed distributions using techniques like logarithmic or power transformations.

Feature Selection: In large datasets, there may be numerous features, not all of which are relevant for analysis or modeling. Feature selection techniques help identify the most informative and important features that contribute to the task at hand.
this is the last step involved in data preprocessing and before ml model training ., it is also called as data normalization 
we apply feature scaling on independent variables , we fit feature scaling with train data and transform on train and test data .

Feature Engineering: This step involves creating new features from the existing ones to improve the predictive power of the model. It may include operations such as creating interaction terms, deriving new variables from existing ones, or applying mathematical functions.

Data Discretization: Sometimes, continuous variables may need to be transformed into discrete or categorical variables. This can be done using techniques such as binning or bucketing.

Data Normalization/Standardization: Normalizing or standardizing the data ensures that different variables are on the same scale, preventing certain variables from dominating others during analysis or modeling.

Handling Imbalanced Data: In classification problems, if the distribution of target classes is highly imbalanced, it can lead to biased models. Techniques like undersampling, oversampling, or generating synthetic samples can be applied to address this issue.

Splitting the Data: Finally, the data is split into training, validation, and testing sets. The training set is used to train the model, the validation set is used for hyperparameter tuning, and the testing set is used to evaluate the final model's performance.













Data Preprocessing (some important points ) It is a techinique to transform noisy ,duplicate ,incomplete inconsistent to accurate ,completeness,consistency ,complete Techiniques

Data cleaning filling missing values ,smooth out noise while identifying outliers and correct inconsistencies in the data 

Data integration it means to merges data from mulitiple sources into a coherent data store ,such as a data warehouse 

Data reduction it is use to reduce the data size by aggregate eliminate redundant features or clustering for instance 

Data Transformation it means data are trnaformed into from appropriate for ml model training such as normalization may be applied whare data are scaled to fall with in smaller range like 0.0 to 1.0 .

Data Discretization it is technique transforms numeric data by mapping values to interval or concept labels it is used to reduce the numbers of values for given continuous attributes to interval form 1,2,3,4,5,6,7,8,9,10 ======> 1-4,5-8



Feature Engineering it is the process to create feature / extract hte feature form the existing features by domain knowledge to increase the performance of machine learning model 
Types of Variable Numerical = Discrete 1,2,3,4,6,7,5,7 Continous 1.23,535.4,46.4,6.4,4.6
Categorical= ordinal is a categorical variable in which the categories can be meaning fully orderd like grade A ,B, C,D,E 
Nominal is same like ordinal variable but there is nothing that indicates an intrinsic order of the labels and in principle there are no order in the nominal variable
Dates and Times ==date time day 
Mixed numbers and categories (labels) are called mixed variables










