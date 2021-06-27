# Frauds Detection Project
 
In this project, a set of data from Talking Data competition was used for two-class classification.
Different ML algorithms were used for this purpose. The data was imbalanced therefore I used several approaches to deal with data including:
* oversampling
* batch reading
* customized approach: I filtered the data with a value of 1 out of 7 GB data and then count the same number of 0 values and added to base data. Results were a CSV file with 800k rows data points but balanced.
* Selecting appropriate hyperparameters to deal with imbalanced data.

In a subproject, a python library for symbolic regression was used on sub-set data. The data normalized and was fed into the algorithm.


# Results
It was concluded that selecting the appropriate hyperparameters could result in almost 90% accuracy. 
The symbolic regression also results in 78% accuracy without any data feathering.
