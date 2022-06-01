# Travel-Insurance-Prediction-Purwadhika-Capstone-Project-3
Data Analysis and Supervised Machine Learning Project for Purwadhika Capstone Project Module 3

This is repository for Purwadhika Data Science and Machine Learning Course.

The data is about travel insurance consisting of features as follows and its data type.


---  ------                --------------  -----  
 0   Agency                44328 ndon-null  object 
 1   Agency Type           44328 non-null  object 
 2   Distribution Channel  44328 non-null  object 
 3   Product Name          44328 non-null  object 
 4   Gender                12681 non-null  object 
 5   Duration              44328 non-null  int64  
 6   Destination           44328 non-null  object 
 7   Net Sales             44328 non-null  float64
 8   Commision (in value)  44328 non-null  float64
 9   Age                   44328 non-null  int64  
 10  Claim                 44328 non-null  object

The packages the were used are pandas, numpy, seaborn, matplotlib, sklearn, category_encoders, imblearn, and ignore warnings.

The data is considered very imbalance from seeing the Claim column in comparing between No's and Yes's. It also has a huge amount of NaN values in Gender column, a couple of negative values in Duration and too high Age value which does not make sense and needs to be fixed.

The distribution of the numerical data (Duration, Net Sales, Commision (in value) and it is right skewed which have a tendency towards smaller values.

