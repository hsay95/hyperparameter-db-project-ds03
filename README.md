## Abstract:

Hyperparameters are parameters that are specified prior to running machine learning algorithms that have a
large effect on the predictive power of statistical models. Knowledge of the relative importance of a
hyperparameter to an algorithm and its range of values is crucial to hyperparameter tuning and creating
effective models.

The hyperparameter database is a public resource with algorithms, tools, and data that allows users to
visualize and understand how to choose hyperparameters that maximize the predictive power of their models.
The hyperparameter database is created by running millions of hyperparameter values, over thousands of
public datasets and calculating the individual conditional expectation of every hyperparameter on the quality
of a model.

Currently, the hyperparameter database analyzes the effect of hyperparameters on the following algorithms:
1. Distributed Random Forest (DRF)
2. Generalized Linear Model (GLM) 
3. Gradient Boosting Machine (GBM) 
4. Naïve Bayes Classifier
5. Stacked Ensembles 
6. Xgboost 
7. Deep Learning Models (Neural Networks).

The hyperparameter database also uses these data to build models that can predict hyperparameters without
search and for visualizing and teaching statistical concepts such as power and bias/variance tradeoff.

As a part of the DMDD team I created a conceptual model and stored all the data into a physical database
by going through the following procedures:
* Scraped JSON files and stores the data in dataframes further saving them in CSV Format.
* Created a conceptual model of the database.
* Perform database normalization – 1NF, 2NF, 3NF.
* Created tables as per the requirement.
* Inserted data into the respective tables from the file which is generated and stored by the Data Science
member.
* Queried database using SQL, created Views (virtual tables) and Functions for various use cases of the
database.
* Performed analytics on the database using queries e.g. getting the best value for the hyperparameter
from the database.

### Please check 'Hyperparameter Database - Final Report.pdf' for a complete overview of the problem and the process I undertook to tackle  it.
