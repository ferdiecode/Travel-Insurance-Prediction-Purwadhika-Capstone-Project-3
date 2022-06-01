# Travel-Insurance-Prediction-Purwadhika-Capstone-Project-3
Data Analysis and Supervised Machine Learning Project for Purwadhika Capstone Project Module 3

This is repository for Purwadhika Data Science and Machine Learning Course.

The data set is a series of information regarding travel insurance with features as follows and its data type.

Agency (name of the agency company), Agency Type (airline or travel agency), Distribution Channel (delivered via online or offline), Product Name (various types of packages that costumer could order), Gender (male or female), Destination (several countries as leisure destinations around the world), Claim (Are they claiming their insurance or not with their travel condition). These columsn are typed as objects.

Duration (the length of travel), Net sales (sum of a companies gross sales minus its returns, allowances, and discounts), Commision in value (the amount of earnings from total sales), Age (the age of the costumer). These columns are already numerical.


The packages the were used were pandas, numpy, seaborn, matplotlib, sklearn, category_encoders, imblearn, and ignore warnings.

The data is considered very imbalance from seeing the Claim column in comparing between No's and Yes's. It also has a huge amount of NaN values in Gender column, a couple of negative values in Duration and too high Age value which does not make sense and needs to be fixed.

The distribution of the numerical data (Duration, Net Sales, Commision (in value) and it is right skewed which have a tendency towards smaller values.

The caterogical data is encoded with one hot and binary method. These features are made into numerical features to include them in the machine learning modeling.

The data was classified in several classification method which are logistic regression, random forest, KNN and decision tree. The outcome shows that Logistic Regression would be the model for this kind of data.

To deal with the imbalance problem random oversampling was used and the metrics was compared before and after oversampling. Furthermore penalised and SMOTE was also used to check how was the model with balanced the oversampling. Afterwards the final model was tuned by adjusting the k neighbors, C and solver in the Logistic Regression with SMOTE model.



